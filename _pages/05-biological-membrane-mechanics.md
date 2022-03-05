---
title: "Biomembrane mechanics"
excerpt: "<img src='/images/research/bio.png' alt=''>"
collection: research
permalink: /research/biological-membrane-mechanics/
header: 
  og_image: "research/bio.png"
---

(In collaboration with [the Laboratory for Computational Cellular Mechanobiology](https://sites.google.com/eng.ucsd.edu/prangamani/home?authuser=0) @ UCSD and  [the Computational Mechanics and Multiphysics Group](https://compphys.me.wisc.edu/) @ UW-Madison)

### Modeling the mechanics in biological membranes during morphological changes

<p style="text-align:center">
<img src="/images/research/bio/phase-diagram-1.png" alt="" width="350px" > 
&nbsp;&nbsp;&nbsp;&nbsp; 
<img src="/images/research/bio/phase-diagram-2.png" alt="" width="350px" > 

<h6>(Two phase diagrams show the potential symmetry-breaking deformation paths during endocytosis captured by the proposed 3D biomembrane simulation framework.)</h6>
</p>

Biomembranes play a central role in various phenomena like locomotion of cells, cell-cell interactions, packaging of nutrients, and in maintaining organelle morphology and functionality. During these processes, the membranes undergo significant morphological changes through deformation, scission, and fusion. Modeling the underlying mechanics of such morphological changes has traditionally relied on reduced order axisymmetric representations of membrane geometry and deformation. Axisymmetric representations, while robust and extensively deployed, suffer from their inability to model symmetry breaking deformations and structural bifurcations. To address this limitation, a 3D computational mechanics framework for high fidelity modeling of biomembrane deformation is presented. The proposed framework brings together Kirchhoff-Love thin-shell kinematics, Helfrich-energy based mechanics, and state-of-the-art numerical techniques for modeling deformation of surface geometries. Lipid bilayers are represented as spline-based surfaces immersed in a 3D space; this enables modeling of a wide spectrum of membrane geometries, boundary conditions, and deformations that are physically admissible in a 3D space. The mathematical basis of the framework and its numerical machinery are presented, and their utility is demonstrated by modeling 3 classical, yet non-trivial, membrane problems: formation of tubular shapes and their lateral constriction, Piezo1-induced membrane footprint generation and gating response, and the budding of membranes by protein coats during endocytosis. For each problem, the full 3D membrane deformation is captured, potential symmetry-breaking deformation paths identified, and various case studies of boundary and load conditions are presented. Using the endocytic vesicle budding as a case study, we also present a "phase diagram" for its symmetric and broken-symmetry states.


### Related publications

Note: <sup>#</sup> - equal contribution

* D Auddya<sup>#</sup>, <b>X Zhang</b><sup>#</sup>, R Gulati, R Vasan, K Garikipati, P Rangamani, S Rudraraju: Biomembranes undergo complex, non-axisymmetric deformations governed by Kirchhoff-Love kinematics and revealed by a three dimensional computational framework, preprint at [arXiv:2101.11929](https://arxiv.org/abs/2101.11929).<br>
