---
title: "Xiaoxuan will give a keynote talk on \"Bayesian Neural Networks for Weak Solution of PDEs with Uncertainty Quantification\" at USNCCM16 on July 27th, 2021."
collection: news
type: "News"
permalink: /news/2021-07-15-news-usnccm16/
date: 2021-07-15
---

I will present a keynote talk on our recent work titled "Bayesian Neural Networks for Weak Solution of PDEs with Uncertainty Quantification" at the [16th U.S. National Congress on Computational Mechanics (USNCCM16)](http://16.usnccm.org/) in the Minisymposium	#309: ["Data-Driven Science with Uncertainty Quantification, Machine Learning, and Optimization"](http://16.usnccm.org/MS_309).

Our talk is scheduled for 14:00 - 14:40 (CT) on Tuesday, July 27th 2021.

Abstract: 

The mathematical treatment of physical systems that are described in terms of field variables leads to partial differential equations (PDEs). However, the large scale solutions of PDEs using state of the art discretization techniques remains an expensive proposition. In this work, a new physics-constrained neural network (NN) approach is proposed to solve PDEs without labels, with a view to enabling high-throughput solutions in support of design and decision-making. Distinct from existing physics-informed NN approaches, where the strong form or weak form of PDEs are used to construct the loss function, we write the loss function of NNs in terms of the residual of PDEs obtained through an efficient, discrete, convolution operator-based, and vectorized implementation. We explore an encoder-decoder NN structure for both deterministic and probabilistic models, with Bayesian NNs (BNNs) for the latter, which allow us to quantify both epistemic uncertainty from model parameters and aleatoric uncertainty from noise in the data. For BNNs, the discretized residual is used to construct the likelihood function. In our approach, both deterministic and probabilistic convolutional layers are used to learn the applied boundary conditions (BCs) and to detect the problem domain. Bboth Dirichlet and Neumann BCs are specified as inputs to NNs, and therefore a single NN can solve for similar physics; i.e., the same PDE, but with different BCs and on a number of problem domains. The trained BNN PDE solvers can make interpolation and also (to a certain extent) extrapolation predictions for BCs that they were not exposed to during training. Such NN solution frameworks assume particular importance in problems, where the PDEs need to be repeatedly solved numerous times with different boundary conditions and on varying domains. We demonstrate the capacity and performance of the proposed framework by applying it to different steady-state and equilibrium boundary value problems with physics that spans diffusion, linear and nonlinear elasticity. 

References 
[1] Xiaoxuan Zhang and Krishna Garikipati. Bayesian neural networks for weak solution of PDEs with uncertainty quantification. arXiv:2101.04879, pages 1-37, 2021.

