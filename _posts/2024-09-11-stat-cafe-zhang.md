---
title: "Stat Cafe - Shuangjie Zhang"
excerpt: "Sparse Bayesian Group Factor Model for Feature Interactions in Multiple Count Tables Data"
layout: single
classes: wide
category: 
  - Stat Cafe
layouts_gallery:
  - url: /assets/images/stat_cafe/Zhang_Sept_11_2024/IMG_1216.jpg
    image_path: /assets/images/stat_cafe/Zhang_Sept_11_2024/IMG_1216.jpg
    alt: "IMG_1216.jpg"
  - url: /assets/images/stat_cafe/Zhang_Sept_11_2024/IMG_1222.jpg
    image_path: /assets/images/stat_cafe/Zhang_Sept_11_2024/IMG_1222.jpg
    alt: "IMG_1222.jpg"
---

<img src="https://jeroda7105.github.io/tamusgsa.github.io/assets/images/stat_cafe/Zhang_Sept_11_2024/IMG_1221.jpg" alt="Header" width="315" style="float: right;"/> 

### Sparse Bayesian Group Factor Model for Feature Interactions in Multiple Count Tables Data

- Time: Wednesday 9/11/2024 from 11:30 AM to 12:30 PM
- Location: BLOC 411
- Sandwiches and drinks provided

### Description
Group factor models have been developed to infer relationships between multiple co-occurring multivariate continuous responses. Motivated by complex count data from multi-domain microbiome studies using next-generation sequencing, we develop a sparse Bayesian group factor model (Sp-BGFM) for multiple count table data that captures the interaction between microorganisms in different domains. Sp-BGFM uses a rounded kernel mixture model using a Dirichlet process (DP) prior with log-normal mixture kernels for count vectors. A group factor model is used to model the covariance matrix of the mixing kernel that describes microorganism interaction.  We construct a Dirichlet-Horseshoe (Dir-HS) shrinkage prior and use it as a joint prior for factor loading vectors. Joint sparsity induced by a Dir-HS prior greatly improves the performance in high-dimensional applications. We further model the effects of covariates on microbial abundances using regression. The semiparametric model flexibly accommodates large variability in observed counts and excess zero counts and provides a basis for robust estimation of the interaction and covariate effects. We evaluate Sp-BGFM using simulation studies and real data analysis, comparing it to popular alternatives. Our results highlight the necessity of joint sparsity induced by the Dir-HS prior, and the benefits of a flexible DP model for baseline abundances. 


### Presentation
<iframe src="https://drive.google.com/file/d/1tN9MfS-UIcedYkMafjpg1VxsRcSM0t8T/preview" width="640" height="480" allow="autoplay"></iframe>

<!-- ### Recording -->

### Gallery

{% include gallery id="layouts_gallery" %}
