---
title: "Stat Cafe - Yeseul Jeon"
excerpt: "A Bayesian Convolutional Neural Network-based Generalized Linear Model"
layout: single
classes: wide
category: 
  - Stat Cafe
layouts_gallery:
  - url: /assets/images/stat_cafe/Jeon_Sept_25_2024/IMG_1230.jpg
    image_path: /assets/images/stat_cafe/Jeon_Sept_25_2024/IMG_1230.jpg
    alt: "IMG_1230.jpg"
  - url: /assets/images/stat_cafe/Jeon_Sept_25_2024/IMG_1232.jpg
    image_path: /assets/images/stat_cafe/Jeon_Sept_25_2024/IMG_1232.jpg
    alt: "IMG_1232.jpg"
---

<img src="https://jeroda7105.github.io/tamusgsa.github.io/assets/images/stat_cafe/Jeon_Sept_25_2024/IMG_1228.jpg?raw=true" alt="Header" width="315" style="float: right;"/> 

### A Bayesian Convolutional Neural Network-based Generalized Linear Model 

- Time: Wednesday 9/25/2024 from 11:30 AM to 12:30 PM
- Location: BLOC 411
- Pizza and drinks provided

### Description
Convolutional neural networks (CNNs) provide flexible function approximations for a
wide variety of applications when the input variables are in the form of images or spatial
data. Although CNNs often outperform traditional statistical models in prediction
accuracy, statistical inference, such as estimating the effects of covariates and
quantifying the prediction uncertainty, is not trivial due to the highly complicated model
structure and overparameterization. To address this challenge, we propose a new
Bayesian approach by embedding CNNs within the generalized linear models (GLMs)
framework. We use extracted nodes from the last hidden layer of CNN with Monte Carlo
(MC) dropout as informative covariates in GLM. This improves accuracy in prediction and
regression coefficient inference, allowing for the interpretation of coefficients and
uncertainty quantification. By fitting ensemble GLMs across multiple realizations from
MC dropout, we can account for uncertainties in extracting the features. We apply our
methods to biological and epidemiological problems, which have both high-dimensional
correlated inputs and vector covariates. Specifically, we consider malaria incidence data,
brain tumor image data, and fMRI data. By extracting information from correlated inputs,
the proposed method can provide an interpretable Bayesian analysis. The algorithm can
be broadly applicable to image regressions or correlated data analysis by enabling
accurate Bayesian inference quickly. 



### Presentation
<iframe src="https://drive.google.com/file/d/1c4AS0T7j_9wYyjyRbtJDNFEsyNvmLQgI/preview" width="640" height="480" allow="autoplay"></iframe>

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/H1NOXgeWSmc?si=BRIu0yWhS-nHxrUG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Gallery

{% include gallery id="layouts_gallery" %}
