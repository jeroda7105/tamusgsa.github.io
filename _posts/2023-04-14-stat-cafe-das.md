---
title: "2023-04-14 Stat Cafe - Snigdha Das"
excerpt: "Blocked Gibbs sampler for hierarchical Dirichlet processes"
layout: single
classes: wide
category:
  - Stat Cafe
---

- Time: Friday 04/14 from 1:00 PM to 2:00 PM
- Location: BLOC 503
- Snacks and drinks will be provided
- [Gallery](/StatCafe/2023-04-14-gallery/)

### Topic

Blocked Gibbs sampler for hierarchical Dirichlet processes

### Abstract

Posterior computation in hierarchical Dirichlet process (HDP) mixture models is an active area of research in nonparametric Bayes inference of grouped data.  Existing literature almost exclusively focuses on the Chinese restaurant franchise (CRF) analogy of the marginal distribution of the parameters, which can mix poorly and is known to have a linear complexity with the sample size. A recently developed slice sampler allows for efficient blocked updates of the parameters but is shown to be statistically unstable in our article. We develop a blocked Gibbs sampler to sample from the posterior distribution of HDP, which produces statistically stable results, is highly scalable with respect to sample size, and is shown to have good mixing. The heart of the construction is to endow the shared concentration parameter with an appropriately chosen gamma prior that allows us to break the dependence of the shared mixing proportions and permits independent updates of certain log-concave random variables in a block.  En route, we develop an efficient rejection sampler for these random variables leveraging piece-wise tangent-line approximations.
