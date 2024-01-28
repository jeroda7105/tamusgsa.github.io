---
title: "2023-02-10 Stat Cafe - Hyunwoong Chang"
excerpt: "Convergence of Markov chain Monte Carlo algorithms in model selection problems"
layout: single
classes: wide
category:
  - Stat Cafe
---

- Time: Friday 02/10 from 1:00 PM to 2:00 PM
- Location: BLOC 503
- Snacks and drinks will be provided
- [Gallery](/StatCafe/2023-02-10-gallery/)

### Topic

Convergence of Markov chain Monte Carlo algorithms in model selection problems

### Abstract

Statistical inference is concerned with methods of using data to obtain information regarding the distribution of data or the data generating model described by a set of parameters. Statistical methods usually get involved with some algorithmic procedure, such as finding the minimizer or approximating the distribution on the parameter space. The Markov chain Monte Carlo (MCMC) algorithm is one of the methods to emulate the distribution by sampling. We consider the convergence of MCMC algorithms in model selection problems where the number of parameters is finite. We will discuss the property of model selection problems, especially why sampling from discrete state spaces is not easier than that from Euclidean spaces. My talk continues with two themes.

1. I will introduce a sufficient condition of rapid mixing of random-walk Metropolis-Hastings (MH) algorithm for general model selection problems. We extend this result to the multiple-try Metropolis (MTM) algorithm, which chooses the proposed state among multiple trials according to some weight function. We prove that MTM can achieve a mixing time bound smaller than that of the MH algorithm by a factor of the number of trials. Our theoretical results suggest a choice of the number of trials for practical use.
2. We discuss a specific model selection problem and its sampling algorithm: order-based sampler for structure learning without score equivalence. While our sampler does not satisfy the sufficient condition of rapid mixing, empirical studies show that mixing of the sampler is fast. We theoretically investigate the mixing behavior of our sampler and provide some intuition why we have relatively good mixing.
