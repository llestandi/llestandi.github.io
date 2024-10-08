---
layout: page
title: CEFIPRA 2023
description: Data reduction and surrogate modelling of transition to turbulence of Rayleigh-Taylor instability data obtained by DNS
img: assets/img/RTI_image.jpg
importance: 1
category: work
related_publications: False
tags: SVD, extreme scale, RTI
---

> ###### **Project identity**
> This is CEFIPRA funded project working with Prof Aditi Sengupta and Tapan Sengupta from [IIT(ISM) Dhanbad](https://www.iitism.ac.in/), India
> - Dates: 2023-2026
> - Keywords:  RTI, extreme scale computing, data reduction
> - Goals:
>   - Advance computing of FOM
>   - Enhance physics understanding
>   - Enable data reduction for very lage datasets
>   - Develop surrogate models of RTI instability 
{: .block-warning }

## Abstract
It is now understood that many problems of fluid mechanics have been solved satisfactorily, except the problem of turbulence. In recent days, even this problem is understood for wall-bounded flows  and some other periodic problems. Understanding the physics and the route of transition to turbulence is not well understood from flow control perspective for free shear layers, as in the case of Rayleigh-Taylor instability (RTI). Thus, solving the problem of Rayleigh-Taylor instability by direct numerical simulation (DNS) has been taken up. This is being pursued by solving compressible three-dimensional Navier-Stokes equations employing high accuracy DNS methodologies (using in-house developed code) of HPC that use 4.19 billion points with commensurate small time steps. However, the DNS data is of size 160GB at each instant of time. Rendering such data is a huge challenge, not only for visualization itself, but also post-processing such data sets using techniques to characterize the nonlinear instability of the transition to turbulence. In this process, reduced data and surrogate models developed by the French side would be of tremendous value. Thus, in this proposal, generating the data by DNS (first step that has been already started) is as important as the concurrent development of the surrogate model and its subsequent use in unravelling the transition to turbulence of the RTI. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RTI_image.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Rayleigh Taylor instability simulation
</div>
