---
title: "Exploring the Efficacy of Statistical and Deep Learning Methods for Large Spatial Datasets: A Case Study"
collection: publications
category: manuscripts
permalink: /publication/2025-03-01-large-spatial-datasets-case-study
excerpt: 'This paper compares statistical and deep learning approaches for large spatial datasets, motivated by the KAUST Competition on Large Spatial Datasets 2023.'
date: 2025-03-01
venue: 'Journal of Agricultural, Biological and Environmental Statistics (JABES)'
paperurl: 'https://doi.org/10.1007/s13253-024-00602-4'
---

**Authors:** A. Hazra, P. Nag, R. Yadav, Y. Sun

Increasingly large and complex spatial datasets pose massive inferential challenges due to high computational and storage costs. Our study is motivated by the KAUST Competition on Large Spatial Datasets 2023, which tasked participants with estimating spatial covariance-related parameters and predicting values at testing sites, along with uncertainty estimates. We compared various statistical and deep learning approaches through cross-validation and ultimately selected the Vecchia approximation technique for model fitting. To overcome the constraints in the R package GpGp, which lacked support for fitting zero-mean Gaussian processes and direct uncertainty estimation, two things that are necessary for the competition, we developed additional R functions. Besides, we implemented certain subsampling-based approximations and parametric smoothing for skewed sampling distributions of the estimators.
