---
title: "2023-02-17 Stat Cafe - Alexander Coulter"
excerpt: "Distributional Regression for CGM Data: Variable Selection Some Time Today, Please"
layout: single
classes: wide
category:
  - Stat Cafe
---

![02172023-Coulter-1.jpg]({{ "/assets/images/stat_cafe/02172023-Coulter-1.jpg" | relative_url }})

- Time: Friday 02/17 from 1:00 PM to 2:00 PM
- Location: BLOC 503
- Snacks and drinks will be provided
- [Gallery](/StatCafe/2023-02-17-gallery/)

### Topic

Distributional Regression for CGM Data: Variable Selection Some Time Today, Please

### Abstract

Continuous glucose monitoring (CGM) devices provide high-frequency blood glucose measurements, giving crucial information on glucose control in patients with diabetes. Functional approaches to this rich data are challenging due to free-living conditions in which CGM data are collected, leading to time-misaligned observations and confounders. Distributional methods can avoid these issues by collapsing all observations into subject-level empirical distribution functions, and a recent variable selection method for quantile functions offers promise for new clinical insights beyond those available from simple statistical summaries. However, existing algorithms for solving the associated optimization problem are prohibitively slow, taking hours or days to work on larger-than-toy datasets. I present a closed-form Newton’s geodesic descent algorithm which completes this task in less than a second, and with improved optimization accuracy. I end with illustrations of variable selection results on a CGM dataset, and discussion of open questions and future directions.
