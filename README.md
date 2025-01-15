This repo stores my professional academic website based on al-folio theme for Jekyll.

# Running in apptainer
First, you need to install [apptainer from sources](https://github.com/apptainer/apptainer/blob/release-1.3/INSTALL.md)

Then, you need to exclude ruby paths from you site config `_config.yaml` in order to avoir parsin at site build as per [troubleshooting page](https://jekyllrb.com/docs/troubleshooting/#configuration-problems):
```yml
exclude:
   - Gemfile
   - Gemfile.lock
   - node_modules
   - vendor/bundle/ # the vendor lines are suggested by the documentation but not useful here.
   - vendor/cache/
   - vendor/gems/
   - vendor/ruby/
   - ruby
   - jekyll_sandbox
```

## Setting up the container
```bash
$ # download a working jekyll image
$ apptainer build jekyll_serve.sif docker://bretfisher/jekyll-serve
# create a sandbox for running the image
$ apptainer build --sandbox jekyll_sandbox jekyll_serve.sif
# You can run the image in interractive mod
$ apptainer shell jekyll_sandbox
# In there, you will likely want to run bundle install 
Apptainer> bundle install
```
At this point you will need to amend the container by installing `imagemagic` for image convertion. You may also need `jupyter` if you want to convert ipynb files. To do so, you can install using: 
```bash
$ apptainer shell --fakeroot --writable jekyll_sandbox
```
To run a fake root session in your contianer to install any required package as usual on a debian machine.
```
Apptainer> apt install imagemagic jupyter -y
```
This will install on the container's system and system python whihc is okay.

## Running the container
Finally, you should be able to serve your site like so:
```bash
# Then you can simply serve your site
$ apptainer exec  --fakeroot --bind "$PWD:/srv/jekyll"  jekyll_sandbox   bundle exec jekyll serve --incremental --host 0.0.0.0 --port 4000
```

Make sure you only have one server running on a given port 😉 otherwise the error is not clear