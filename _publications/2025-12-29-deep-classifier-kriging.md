---
title: "Deep classifier kriging for probabilistic spatial prediction of air quality index"
collection: publications
category: manuscripts
permalink: /publication/2025-12-29-deep-classifier-kriging
excerpt: 'This paper proposes deep classifier kriging (DCK), a distribution-free deep learning framework for probabilistic spatial prediction with data fusion.'
date: 2025-12-29
venue: 'arXiv preprint arXiv:2512.23474'
paperurl: 'https://arxiv.org/abs/2512.23474'
---

**Authors:** J. Chen, P. Nag, H. Judy-Wang, Y. Sun

Accurate spatial interpolation of the air quality index (AQI), computed from concentrations of multiple air pollutants, is essential for regulatory decision-making, yet AQI fields are inherently non-Gaussian and often exhibit complex nonlinear spatial structure. Classical spatial prediction methods such as kriging are linear and rely on Gaussian assumptions, which limits their ability to capture these features and to provide reliable predictive distributions. In this study, we propose *deep classifier kriging* (DCK), a flexible, distribution-free deep learning framework for estimating full predictive distribution functions for univariate and bivariate spatial processes, together with a *data fusion* mechanism that enables modeling of non-collocated bivariate processes and integration of heterogeneous air pollution data sources. Through extensive simulation experiments, we show that DCK consistently outperforms conventional approaches in predictive accuracy and uncertainty quantification. We further apply DCK to probabilistic spatial prediction of AQI by fusing sparse but high-quality station observations with spatially continuous yet biased auxiliary model outputs, yielding spatially resolved predictive distributions that support downstream tasks such as exceedance and extreme-event probability estimation for regulatory risk assessment and policy formulation.
