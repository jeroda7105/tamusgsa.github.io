---
title: "Stat Cafe - Jacob Andros"
excerpt: "Robust Distributed Learning of Functional Data From Simulators through Data Sketching"
layout: single
classes: wide
category: 
  - Stat Cafe
layouts_gallery:
  - url: /assets/images/stat_cafe/Andros_Jan_29_2024/IMG_0133.jpg
    image_path: /assets/images/stat_cafe/Andros_Jan_29_2024/IMG_0133.jpg
    alt: "IMG_0133.jpg"
  - url: /assets/images/stat_cafe/Andros_Jan_29_2024/IMG_0128.jpg
    image_path: /assets/images/stat_cafe/Andros_Jan_29_2024/IMG_0128.jpg
    alt: "IMG_0128.jpg"
  - url: /assets/images/stat_cafe/Andros_Jan_29_2024/IMG_0124.jpg
    image_path: /assets/images/stat_cafe/Andros_Jan_29_2024/IMG_0124.jpg
    alt: "IMG_0124.jpg"
  - url: /assets/images/stat_cafe/Andros_Jan_29_2024/IMG_0117.jpg
    image_path: /assets/images/stat_cafe/Andros_Jan_29_2024/IMG_0117.jpg
    alt: "IMG_0117.jpg"
---

- Time: Monday 1/22/2024 from 11:40 AM to 12:30 PM
- Location: BLOC 448
- Pizza and drinks provided
<!-- - [Presentation]({{ "/assets/files/stat_cafe/Andros_Jan_29_2024/StatCafe_Andros_slides.pdf" | relative_url }}) -->
<!-- - [Recording]() -->

### Description
Emerging distributed Bayesian learning frameworks partition raw data into shards and distribute computations of these shards across machines. While this strategy mitigates data storage costs and improves computation within each machine, concerns arise regarding the sensitivity of distributed inference to shard selection. Our research proposes an innovative alternative. Instead of creating data shards, we employ multiple random matrices to construct multiple random linear projections, or "random sketches," of the complete dataset. Posterior inference on functional data models is performed using random sketches on various machines in parallel. These individual inferences are then combined across machines at a central server. By aggregating inference across diverse random matrices, our approach proves resilient to the selection of data sketches, leading to the development of novel robust distributed Bayesian learning approach. An important advantage of our approach is its ability to maintain the privacy of sampling units, as the inference is based on random data sketches that do not allow the recovery of raw data.

### Presentation
<iframe src="https://drive.google.com/file/d/13YoyF3WMtYrIHWHBd3RxaXjGLu5alSZo/preview" width="640" height="480" allow="autoplay"></iframe>

### Recording (Coming Soon)


### Gallery

{% include gallery id="layouts_gallery" %}
