---
title: "2022-10-27 Stat Cafe - Dr. Jaiswal"
excerpt: "Thompson Sampling with Fractional Posterior: Formulation and Regret Analysis"
layout: single
classes: wide
category:
  - Stat Cafe
---

- Time: Monday 10/27 from 2:30 PM to 3:30 PM
- Location: BLOC 502
- Snacks and drinks will be provided
- [Gallery](/StatCafe/2022-10-27-gallery/)

### Topic

Thompson Sampling with Fractional Posterior: Formulation and Regret Analysis

### Abstract

The stochastic multiarmed bandit (MAB) problem is one of the most popular frameworks for sequential decision-making. It is widely used to model a variety of sequential decision-making problems such as add placement, website optimization, mobile health, packet routing, clinical trials, and revenue management. Thompson sampling (TS) is among the earliest known algorithms to solve stochastic MAB problems. Despite of empirical success of TS, its theoretical analysis is rather limited and requires restrictive modeling assumptions. In this talk, we will learn about a close variant of TS, named α-TS, that, unlike TS, uses a fractional or α-posterior (0 < α < 1) instead of the standard posterior distribution to compute an arm selection policy. We will discuss the near-optimal instance-dependent and instance-independent frequentist regret bounds of α-TS with general prior distribution for sub-Gaussian rewards. We will observe that near-optimal frequentist regret bounds of α-TS are derived under a very mild regularity condition on the prior distribution that only requires the prior to place positive mass in an appropriate Rényi neighborhood of the true reward distribution. Moreover, we will also see that the regret analysis of α-TS does not require additional structural properties such as closed-form posteriors or conjugate priors, which is common in the existing literature. In the end, we will also discuss some empirical results comparing the performance of α-TS with TS and other popular MAB algorithms.
