---
title: "2022-10-20 Stat Cafe - Dr. Laha"
excerpt: "Optimal dynamic treatment regimes via smooth surrogate losses"
layout: single
classes: wide
category:
  - Stat Cafe
---

- Time: Monday 10/20 from 2:30 PM to 3:30 PM
- Location: BLOC 503
- Snacks and drinks will be provided
- [Gallery](/StatCafe/2022-10-20-gallery/)

### Topic

Optimal dynamic treatment regimes via smooth surrogate losses

### Abstract

Large health care data repositories such as electronic health records (EHR) open
new opportunities to derive individualized treatment strategies for complicated diseases
such as sepsis. In this talk, I will discuss the problem of estimating sequential treatment
policies tailored to a patient&#39;s individual characteristics, often referred to as dynamic
treatment regimes (DTRs), which is a special class of offline reinforcement learning
problems. Our main objective will be to find the optimal treatment policy that maximizes a
discontinuous value function through direct maximization of Fisher consistent surrogate loss
functions. In this regard, we demonstrate that a large class of concave surrogates fails to be
Fisher consistent -- a behavior that differs from the classical binary classification problems.
We further characterize a non-concave family of Fisher consistent smooth surrogate
functions, which can be optimized via gradient descent using off-the-shelf machine learning
algorithms. Compared to the existing direct search approach under the support vector
machine framework (Zhao et al., 2015), our proposed policy learning method via surrogate
loss optimization (DTRESLO) method is more computationally scalable to large sample
sizes and allows for broader functional classes for treatment policies. We establish
theoretical properties for our proposed estimator of the optimal policy and obtain a sharp
upper bound on the regret corresponding to our DTRESLO method. The finite sample
performance of our proposed estimator is evaluated through extensive simulations. Finally,
we illustrate the working principles and benefits of our method using EHR data from sepsis
patients admitted to intensive care units.
