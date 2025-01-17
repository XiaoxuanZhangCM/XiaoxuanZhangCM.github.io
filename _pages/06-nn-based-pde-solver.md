---
layout: archive
title: "Machine learning for PDE solutions"
permalink: /research/nn-based-pde-solver/
author_profile: true
---

### Develop data-driven models for weak solutions of PDE with uncertainty quantification

<p style="text-align:center">
<img src="/images/research/pde/pde-solver.png" alt="" width="800px" > 

<h6>(Summary of the setup of NN-based PDE solver with some preliminary NN results with uncertainty quantification.)</h6>
</p>

Solving partial differential equations (PDEs) is the canonical approach for understanding the behavior of physical systems. However, large scale solutions of PDEs using state of the art discretization techniques remains an expensive proposition. In this work, a new physics-constrained neural network (NN) approach is proposed to solve PDEs without labels, with a view to enabling high-throughput solutions in support of design and decision-making. Distinct from existing physics-informed NN approaches, where the strong form or weak form of PDEs are used to construct the loss function, we write the loss function of NNs based on the discretized residual of PDEs through an efficient, convolutional operator-based, and vectorized implementation. We explore an encoder-decoder NN structure for both deterministic and probabilistic models, with Bayesian NNs (BNNs) for the latter, which allow us to quantify both epistemic uncertainty from model parameters and aleatoric uncertainty from noise in the data. For BNNs, the discretized residual is used to construct the likelihood function. In our approach, both deterministic and probabilistic convolutional layers are used to learn the applied boundary conditions (BCs) and to detect the problem domain. As both Dirichlet and Neumann BCs are specified as inputs to NNs, a single NN can solve for similar physics, but with different BCs and on a number of problem domains. The trained surrogate PDE solvers can also make interpolating and extrapolating (to a certain extent) predictions for BCs that they were not exposed to during training. Such surrogate models are of particular importance for problems, where similar types of PDEs need to be repeatedly solved for many times with slight variations. We demonstrate the capability and performance of the proposed framework by applying it to steady-state diffusion, linear elasticity, and nonlinear elasticity.

### Related publications

* <b>X Zhang</b>, K Garikipati: Bayesian neural networks for weak solution of PDEs with uncertainty quantification, preprint at [arXiv:2101.04879](https://arxiv.org/abs/2101.04879). 
