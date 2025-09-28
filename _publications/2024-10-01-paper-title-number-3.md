---
title: "Bivariate DeepKriging for Computationally Efficient Spatial Interpolation of Large-scale Wind Fields"
collection: publications
category: manuscripts
permalink: /publication/2024-10-01-paper-title-number-3
excerpt: 'In this paper DeepKriging has been extended to bivariate spatial processes, incorporating connections to the Linear Model of Coregionalization.'
date: 2025
venue: 'Technometrics'
paperurl: 'https://doi.org/10.1080/00401706.2025.2453197'
---

High spatial resolution wind data play a crucial role in various fields such as climate, oceanography, and meteorology. However, spatial interpolation or downscaling of bivariate wind fields, characterized by velocity in two dimensions, poses a challenge
due to their non-Gaussian nature, high spatial variability, and heterogeneity. While
cokriging is commonly employed in spatial statistics for predicting bivariate spatial
fields, it is suboptimal for non-Gaussian processes and computationally prohibitive
for large datasets. In this paper, we introduce bivariate DeepKriging, a novel method
utilizing a spatially dependent deep neural network (DNN) with an embedding layer
constructed by spatial radial basis functions for predicting bivariate spatial data.
Additionally, we devise a distribution-free uncertainty quantification technique based
on bootstrap and ensemble DNN. We establish the theoretical basis for bivariate
DeepKriging by linking it with the Linear Model of Coregionalization (LMC). Our
proposed approach surpasses traditional cokriging predictors, including those utilizing commonly used covariance functions like the linear model of co-regionalization and parsimonious bivariate Mat´ern covariance. We demonstrate the computational
efficiency and scalability of the proposed DNN model, achieving computation speeds
approximately 20 times faster than conventional techniques. Furthermore, we apply
the bivariate DeepKriging method to wind data across the Middle East region at
506,771 locations, showcasing superior prediction performance over cokriging predictors while significantly reducing computation time.
