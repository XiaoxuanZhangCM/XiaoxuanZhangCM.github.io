---
title: "Fracture modeling"
excerpt: "<img src='/images/research/efem.png' alt=''>"
collection: research
permalink: /research/fracture-modeling/
header: 
  og_image: "research/efem.png"
---

### Model non-planar fracture propagation in three-dimensional solids with the embedded finite element method


<p style="text-align:center">
<img src="/images/research/efem/efem-3pb-iso.gif" alt="" width="250px" > &nbsp;&nbsp;&nbsp;&nbsp; <img src="/images/research/efem/efem-3pb-crk.gif" alt="" width="250px" >

<h6>(left: evolution of iso-surfaces of the level set scalar; right: crack propagation)</h6>
</p>

<p style="text-align:center">

<img src="/images/research/efem/efem-torsion-crk.gif" alt="" width="500px" > 

<h6>(crack propagation)</h6>
</p>

We developed an advanced failure surface propagation concept based on the marching cubes algorithm initially proposed in the field of computer graphics and applies it to the embedded finite element method. When modeling three-dimensional (3D) solids at failure, the propagation of the failure surface representing a crack or shear band should not exhibit a strong sensitivity to the details of the finite element discretization. This results in the need for a propagation of the discrete failure zone through the individual finite elements, which is possible for finite elements with embedded strong discontinuities. Whereas for two-dimensional calculations the failure zone propagation location is easily predicted by the maximal principal stress direction, more advanced strategies are needed to achieve a smooth failure surface in 3D simulations. An example for such method is the global tracking algorithm, which predicts the crack path by a scalar level set function computed on the basis of the solution of a simplified heat conduction like problem. Its prediction may though lead to various scenarios on how the failure surface may propagate through the individual finite elements. In particular, for a hexahedral eight-node finite element, 256 such cases exist. To capture all those possibilities, the marching cubes algorithm is combined with the global tracking algorithm and the finite elements with embedded strong discontinuities in this work. In addition, because many of the possible cases result in non-planar failure surfaces within a single finite element and because the local quantities used to describe the kinematics of the embedded strong discontinuities are physically meaningful in a strict sense only for planar failure surfaces, a remedy for such scenarios is proposed. 

### Model non-planar fracture propagation in electromechanical coupled materials with the embedded finite element method

<p style="text-align:center">
<img src="/images/research/efem/eefem-tension-crk.gif" alt="" width="200px" > &nbsp;&nbsp;&nbsp;&nbsp; <img src="/images/research/efem/eefem-tension-elec.gif" alt="" width="200px" >

<h6>(left: crack propagation; right: evolution of the electric field)</h6>
</p>

We proposed new finite elements with embedded strong discontinuities to model failure in three dimensional electromechanical coupled materials. We decompose the coupled boundary value problem into a continuous global part and into a discontinuous local part where strong discontinuities in the displacement field and electric potential are introduced. Those are incorporated into general three-dimensional brick finite elements through nine mechanical separation modes and three new electrical separation modes. All the local enhanced parameters related to those modes can be statically condensed out on the element level, yielding a computationally efficient framework to model failure in electromechanical coupled materials. Impermeable electric boundary conditions are assumed along the strong discontinuities. Their initiation and orientation is detected through a configurational force driven failure criterion. A marching cubes based crack propagation concept is used to obtain smooth failure surfaces in the three dimensional problems of interest. 

### Related publications

* C Linder, <b>X Zhang</b>: [Three-dimensional finite elements with embedded strong discontinuities to model failure in electromechanical coupled materials](https://www.sciencedirect.com/science/article/pii/S0045782514000346), Computer Methods in Applied Mechanics and Engineering, 273, 143-160, 2014.
* C Linder, <b>X Zhang</b>: [A marching cubes based failure surface propagation concept for three‐dimensional finite elements with non‐planar embedded strong discontinuities of higher‐order kinematics](https://onlinelibrary.wiley.com/doi/full/10.1002/nme.4546), International Journal for Numerical Methods in Engineering, 96, 339-372, 2013.

