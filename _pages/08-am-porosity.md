---
title: "Data-driven modeling of crack initiation in 3D printed metal parts"
excerpt: "<img src='' alt=''>"
collection: research_current
permalink: /research/am-porosity
header: 
  og_image: ""
---

(In collaboration with researchers from Sandia National Laboratories)

<p style="text-align:center">
<img src="/images/research/am/am.png" alt="" width="600px" > 

<h6>(3D printed 17-4PH stainless steel dogbone specimen with computed tomography (CT) scans that reveal the internal porosity <a href="https://www.sciencedirect.com/science/article/pii/S0045782520306563">source</a>)</h6>

</p>

Compared to conventional metal fabrication processes, additive manufacturing (AM) offers advantages in several aspects, such as handling complex geometries, rapid prototyping, reduced material wastes, etc. However, parts made by AM tend to have higher variation in their mechanical properties due to multiple factors, such as porosity, residual stresses, surface roughness, etc. 

In this work we employ an encoder-decoder convolutional neural network to predict the failure locations of porous metal tension specimens based only on their initial porosities. The process we model is complex, with a progression from initial void nucleation, to saturation, and ultimately failure. The objective of predicting failure locations presents an extreme case of class imbalance since most of the material in the specimens do not fail. In response to this challenge, we develop and demonstrate the effectiveness of data- and loss-based regularization methods. Since there is considerable sensitivity of the failure location to the particular configuration of voids, we also use variational inference to provide uncertainties for the neural network predictions. We connect the deterministic and Bayesian convolutional neural networks at a theoretical level to explain how variational inference regularizes the training and predictions. We demonstrate that the resulting predicted variances are effective in ranking the locations that are most likely to fail in any given specimen.

### Related publications

Note: <sup>#</sup> - equal contribution

W Bridgman<sup>#</sup>, <b>X Zhang</b><sup>#</sup>, G Teichert, M Khalil, K Garikipati, R Jones<sup>$</sup>. A heteroencoder architecture for prediction of failure locations in porous metals using variational inference, preprint at [arXiv:2202.00078](https://arxiv.org/abs/2202.00078). 
