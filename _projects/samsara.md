---
layout: page
title: "SAMSARA"
description: Smart Additive Manufacturing for Sustainability and Reliability
img: /assets/img/SAMSARA/DALLE_SAMSARA_Visual.jpg
importance: 1
category: work
related_publications: False
tags: WAAM, physics based simulation, data driven modeling, in process monitoring, circular economy
---

<div class="col">
    <div class="col-sm mt-3 mt-md-0" style="width: 50%; max-width: 400px; margin: 0 auto;">
        <img src="/assets/img/SAMSARA/DALLE_SAMSARA_Visual.jpg" alt="Embracing AI with this DALL-E generated catch" style="width: 100%; height: auto;">
    </div>
    <div class="col-sm mt-3 mt-md-0" style="display: flex; justify-content: center;">
        {% include audio.liquid path="/assets/audio/SAMSARA_notebookLM.wav" controls=true %}
    </div>
</div>
<div class="caption">
    Embracing AI's power is paramount for reaching Industry 4.0 goals. Illustration generated by stable diffusion model DALL-E on Jan 15, 2025. Below, a podcast format automatically generated by Google's NotebookLM in which you can learn a lot about this project.
</div>

The SAMSARA project, coordinated by M. Jhon and myself, has been awarded funding for 3 years under ANR-PRCI 2024 joint call with Singapore NRF. The project focuses on **Smart Additive Manufacturing for Sustainability and Reliability**, specifically using Wire Arc Additive Manufacturing (WAAM) for repair processes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SAMSARA/logo_ANR.jpg" title="Agence nationale de la recherche" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SAMSARA/logo_NRF.jpg" title="National Research Foundation" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    SAMSARA is a project jointly funded by Singapore NRF and France ANR.
</div>


## Objective
The primary goal is to integrate data-driven techniques with physics-based computer models to optimize the WAAM process for repair. This includes developing strategies to avoid manufacturing defects, reduce energy consumption, and maintain sufficient mechanical properties. The project aims to demonstrate the feasibility of integrating in-process monitoring and physics-based simulations for effective repair of complex steel workpieces.

## Circular Economy Focus
SAMSARA aligns with the principles of the Circular Economy, aiming to reduce waste and carbon emissions by using WAAM to repair and extend the lifespan of products. The project seeks to use Industry 4.0 technologies to avoid waste and repair parts.

## Key Technologies
The project focuses on WAAM, which is recognized for its potential to repair or fabricate replacement parts. The project will develop Smart Manufacturing and decision-aid tools for the process definition of industrial component repair. This includes high-fidelity physics-based computer simulations to predict defect formation and mechanical properties. It also involves the development of surrogate models, a type of Reduced Order Model (ROM), to make the simulations computationally efficient.

## Addressing WAAM Defects
The project will focus on addressing defects that occur in WAAM, such as porosity, humping, trickling, and part distortion, which are linked to heat flux management during material deposition. It will also address the complexity of heat management in repair, specifically when combining massive sections of a workpiece with slim sections to be repaired.

## Methodology

The project will use a combination of physics-based simulations, in-process monitoring, and data-driven surrogate modeling. The project is organized into five work packages (WP):
    *   **WP0:** Project management and dissemination.
    *   **WP1:** Validated physics-based simulation, focusing on developing high-fidelity simulations of the WAAM process and the effects of defects.
    *   **WP2:** In-process monitoring and carbon footprint management, including upgrading the existing WAAM platform with new sensors and developing new monitoring criteria.
    *   **WP3:** Data-driven surrogate modeling, focused on integrating simulation and experimental data to predict defects.
    *   **WP4:** Demonstration of the method on an industrially relevant repair geometry.
<div class="col">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SAMSARA/WPs.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
       <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SAMSARA/gantt.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of work packages organization.
</div>

## Expected Impact
 The project is expected to optimize the WAAM process for repairs, making it more applicable for industrial use. The project also aims to advance smart manufacturing by bridging the gap between process simulation and practical experiments and make reduced order modeling more easily available for industrial use.  Additionally, it will provide training opportunities for young researchers and foster collaborations between France and Singapore.

*The SAMSARA project aims to make WAAM a more effective and sustainable process for repairing metallic parts, contributing to the goals of the Circular Economy.*

# Project Partners

The project is a collaboration between French and Singaporean institutions. The French institutions are GeM, LS2N and IMN. The Singaporean institution is IHPC. Each of these institutions has specific expertise in areas including, but not limited to, computer science, mechanical engineering, materials science, and process simulation.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SAMSARA/logo_GeM.png" title="GeM Logo" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SAMSARA/logo_LS2N.png" title="LS2N Logo" class="img-fluid rounded " %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SAMSARA/logo_IMN.png" title="IMN" class="img-fluid rounded " %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SAMSARA/logo_IHPC.png" title="IPHC" class="img-fluid rounded " %}
    </div>
</div>
<div class="caption">
    The Four partners involved in this project : GeM/Ecole Centrale de Nantes, LS2N/Nantes Université, IMN/CNRS and the Institute of High Performance Computing (IHPC) at A*Star, Singapore.
</div>

| Name             | Current Position          | Role in Project                                         | Lab | Country   |
|-----------------|---------------------------|---------------------------------------------------------|--------------------------|-----------|
| **Lucas Lestandi**   | Associate Professor       | PI (France) Sci. Leader at GeM, WP 0, 3 & 4 leader  | GeM                        | FR        |
| Guillaume Racineux| Full Professor           | WP 3, 4                                                 | GeM                         | FR        |
| TBD (hiring)              | PhD student              | WP 1, 2, 3, 4                                    | GeM                        | FR        |
| **Mathieu Ritou**    | Associate Professor      |  Sci. leader at LS2N, WP 2 leader                   | LS2N                         | FR        |
| Elodie Paquet      | Associate Professor       | WP 2, 4                                                 | LS2N                         | FR        |
| TBD (hiring)              | Post Doc                | WP 2, 4                                                 | LS2N                        | FR        |
| **Emmanuel Bertrand**| Associate Professor       | Sci. leader at IMN, WP 1, 2, 4                   | IMN                         | FR        |
| Laurent Couturier | Associate Professor       | WP 2, 4                                                 | IMN                       | FR        |
| TBD (hiring)            | Master student            | WP1                                                   | IMN                         | FR        |
| **Mark Jhon**      | Principal Scientist       | PI (Singapore), Sci. leader at IHPC, WP 0 & 1 leader | IHPC | SG |
| Jerry Quek       | Principal Scientist       | WP 1                                                  | IHPC                         | SG        |
| Chao Tang        | Senior Scientist         | WP 1, 4                                                 | IHPC                       | SG        |
| Kartikey Joshi   | Senior Scientist         | WP 1, 3                                                 | IHPC                      | SG        |


Additional notes about the personnel roles:
*   **Project Coordinators:** The project is jointly coordinated by **Lucas Lestandi** in France and **Mark Jhon** in Singapore.
*   **Scientific Leaders:**  Besides the coordinators, **Mathieu Ritou** is a scientific leader at LS2N, and **Emmanuel Bertrand** is a scientific leader at IMN.
*   **PhD Student (GeM/Centrale Nantes):** One PhD student will be hired to work across multiple work packages.
*   **Postdoctoral Researcher (LS2N/Nantes Université):**  A post-doctoral researcher will be hired and will work on the in-process monitoring and experiments.
*   **Master Student (IMN):** A master student will be hired to work on the mechanical characterization of the builds.

