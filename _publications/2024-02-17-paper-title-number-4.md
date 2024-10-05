---
title: "Efficient Large-scale Nonstationary Spatial Covariance function estimation using Convolutional Neural Networks"
collection: publications
category: manuscripts
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper provides a data driven scalable approach for fitting Nonstationary Matern covariance for large datasets.'
date: 2024-09
venue: 'Journal of Computational and Graphical Statistics (JCGS)'
paperurl: ', https://doi.org/10.1080/10618600.2024.2402277'
citation: 'Nag, Pratik, Yiping Hong, Sameh Abdulah, Ghulam A. Qadir, Marc G. Genton, and Ying Sun. "Efficient Large-scale Nonstationary Spatial Covariance Function Estimation Using Convolutional Neural Networks." Journal of Computational and Graphical Statistics just-accepted (2024): 1-22.'
---

Spatial processes observed in various fields, such as climate and environmental science, often occur at large-scale and demonstrate spatial nonstationarity. However, fitting a Gaussian process with a nonstationary Matérn covariance is challenging, as it requires handling the complexity and computational demands associated with modeling the varying spatial dependencies over large and heterogeneous domains. Previous studies in the literature have tackled this challenge by employing spatial partitioning techniques to estimate the parameters that vary spatially in the covariance function. The selection of partitions is an important consideration, but it is often subjective and lacks a data-driven approach. To address this issue, in this study, we utilize the power of Convolutional Neural Networks (ConvNets) to derive subregions from the nonstationary data by employing a selection mechanism to identify subregions that exhibit similar behavior to stationary fields. We rely on the ExaGeoStat software for large-scale geospatial modeling to implement the nonstationary Matérn covariance for large-scale exact computation of nonstationary Gaussian likelihood. We also assess the performance of the proposed method with synthetic and real datasets at large-scale. The results revealed enhanced accuracy in parameter estimations when relying on ConvNet-based partition compared to traditional user-defined approaches.
