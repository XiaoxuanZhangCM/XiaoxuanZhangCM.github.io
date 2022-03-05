---
title: "Lithium-ion batteries"
excerpt: "<img src='/images/research/libs.png' alt=''>"
collection: research
permalink: /research/mechanics-in-lithium-ion-batteriesl/
header: 
  og_image: "research/libs.png"
---

(In collaboration with [the Energy Technologies Department at Bosch RTC](https://www.bosch.com/research/know-how/research-experts/jake-christensen-ph-d/) @ Sunnyvale, CA)
### Model the coupling between mechanics and electrochemical process in lithium-ion batteries

<p style="text-align:center">
<img src="/images/research/libs/lib-1d-ill.png" alt="" width="600px" > 
<h6>(Illustration of the mechanical effects, including porosity variation and the transport distance change, captured by the proposed multiphysics model.)</h6>
</p>


For a battery cell, both the porosity of the electrodes/separator and the transport distance of charged species can evolve due to mechanical deformation arising from either lithium intercalation-induced swelling and contraction of the active particles or externally applied mechanical loading. To describe accurately the coupling between mechanical deformation and the cell's electrochemical response, we extend Newman's DualFoil model to allow variable, non-uniform porosities in both electrodes and the separator, which are dynamically updated based on the electrochemical and mechanical states of the battery cell. In addition, the finite deformation theory from continuum mechanics is used to modify the electrochemical transport equations to account for the change of the charged species transport distance. The proposed coupled electrochemomechanical model is tested with a parameterized commercial cell. Our simulation results confirm that mass conservation is satisfied with the new formulation. We further show that mechanical effects have a significant impact on the cell's electrochemical response at high charge/discharge rates.

### Multiscale modeling of three-dimensional lithium-ion batteries

<p style="text-align:center">
<img src="/images/research/libs/lib-3d-ill.png" alt="" width="600px" > 
<h6>(Illustration of the information flow of the proposed multiscale multiphysics battery model, which captures both the essential physics occurring in the sandwich layer thickness direction and the thermomechanical behavior on the cell level.)</h6>
</p>

<p style="text-align:center">
<img src="/images/research/libs/lib-3d-flowchart.png" alt="" width="600px" > 
<h6>(Simulation flowchart for the multiscale multiphysics battery model.)</h6>
</p>

<p style="text-align:center">
<img src="/images/research/libs/lib-3d-18650.png" alt="" width="600px" > 
<h6>(Simulation setup and results for an 18650 cell.)</h6>
</p>


Thermal and mechanical effects play a vital role in determining the electrochemical behavior of lithium-ion batteries (LIBs). Non-uniform temperature distribution and mechanical deformation can result in uneven electrochemical states, leading to spatially varying aging rates that significantly shorten cell lifetime. In order to improve simulation accuracy and thus the quality of computational battery design optimization, it is therefore essential to capture these coupled phenomena in a simulation model of a full battery cell. In this work, an electro-chemo-thermo-mechanical coupled framework is proposed to simulate LIBs in the three-dimensional space. In this new framework, a recently proposed one-dimensional electrochemical model, which includes the impact of mechanical deformation and local lithiation state on the effective transport properties of the charged species, is coupled with a three-dimensional thermomechanical model. A unique coupling scheme is proposed to handle information exchange between these two models. This framework allows us to accurately and efficiently study the behavior of three-dimensional cells with realistic geometry and resolve the spatial variation of interested fields. Two commercial cells are studied to show the performance of the newly proposed battery simulation framework.


### Related publications

* <b>X Zhang</b>, M Klinsmann, S Chumakov, X Li, SU Kim, M Metzger, M Besli, R Klein, C Linder, J Christensen: [A Modified Electrochemical Model to Account for Mechanical Effects Due to Lithium Intercalation and External Pressure](https://iopscience.iop.org/article/10.1149/1945-7111/abe16d/meta) Journal of the Electrochemical Society 168 (2), 020533, 2021.

* <b>X Zhang</b>, S Chumakov, X Li, M Klinsmann, SU Kim, C Linder, J Christensen: [An electro-chemo-thermo-mechanical coupled three-dimensional computational framework for lithium-ion batteries](https://iopscience.iop.org/article/10.1149/1945-7111/abd1f2/meta) Journal of the Electrochemical Society 167 (16), 160542, 2020.
