---
title: "Stat Cafe - Samuel Gailliot"
excerpt: "Data Sketching and Stacking: A Confluence of Two Strategies for Predictive Inference in Gaussian Process Regressions with High-Dimensional Features"
layout: single
classes: wide
category: 
  - Stat Cafe
layouts_gallery:
  - url: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0199.jpg
    image_path: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0199.jpg
    alt: "IMG_0199.jpg"
  - url: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0204.jpg
    image_path: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0204.jpg
    alt: "IMG_0204.jpg"
  - url: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0209.jpg
    image_path: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0209.jpg
    alt: "IMG_0209.jpg"
  - url: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0260.jpg
    image_path: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0260.jpg
    alt: "IMG_0260.jpg"
  - url: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0267.jpg
    image_path: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0267.jpg
    alt: "IMG_0267.jpg"
  - url: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0294.jpg
    image_path: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0294.jpg
    alt: "IMG_0294.jpg"
  - url: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0307.jpg
    image_path: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0307.jpg
    alt: "IMG_0307.jpg"
  - url: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0322.jpg
    image_path: /assets/images/stat_cafe/Gailliot_Feb_19_2024/IMG_0322.jpg
    alt: "IMG_0322.jpg"
---

- Time: Monday 2/19/2024 from 11:40 AM to 12:30 PM
- Location: BLOC 448
- Pizza and drinks provided
<!-- - [Presentation]({{ "/assets/files/stat_cafe/Gailliot_Feb_19_2024/StatCafe_Gailliot_slides.pdf" | relative_url }}) -->
<!-- - [Recording](https://youtu.be/Cqgz6SkTACU?si=3D-9b-n0BWyOmJut) -->

### Description
This article focuses on drawing computationally-efficient predictive inference from Gaussian process (GP) regressions with a large number of features when the response is conditionally independent of the features given the projection to a noisy low dimensional manifold. Bayesian estimation of the regression relationship using Markov Chain Monte Carlo and subsequent predictive inference is computationally prohibitive and may lead to inferential inaccuracies since accurate variable selection is essentially impossible in such high-dimensional GP regressions. As an alternative, this article proposes a strategy to sketch the high-dimensional feature vector with a carefully constructed sketching matrix, before fitting a GP with the scalar outcome and the sketched feature vector to draw predictive inference. The analysis is performed in parallel with many different sketching matrices and smoothing parameters in different processors, and the predictive inferences are combined using Bayesian predictive stacking. Since posterior predictive distribution in each processor is analytically tractable, the algorithm allows bypassing the robustness issues due to convergence and mixing of MCMC chains, leading to fast implementation with very large number of features.  Simulation studies show superior performance of the proposed approach with a wide variety of competitors. The approach outperforms competitors in drawing point prediction with predictive uncertainties of outdoor air pollution from satellite images.

### Presentation
<iframe src="https://drive.google.com/file/d/1aB6kvyj3Jdf4HPEbKUmdBQrnx93hrDH0/preview" width="640" height="480" allow="autoplay"></iframe>

### Recording 
<iframe width="560" height="315" src="https://www.youtube.com/embed/Cqgz6SkTACU?si=cLOBYMycwvPkiAww" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Gallery

{% include gallery id="layouts_gallery" %}
