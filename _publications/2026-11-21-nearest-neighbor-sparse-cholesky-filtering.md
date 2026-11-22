---
title: "Nearest-Neighbor Sparse Cholesky Decomposition with Applications to High-Dimensional Spatio-Temporal Filtering"
collection: publications
category: manuscripts
permalink: /publication/2026-11-21-nearest-neighbor-sparse-cholesky-filtering
excerpt: 'This paper proposes a three-stage nearest-neighbor sparse Cholesky decomposition that turns the conditional sparsity of Vecchia approximations into a sparse posterior covariance factor for fast, accurate high-dimensional spatio-temporal filtering.'
date: 2026-11-21
venue: 'Submitted manuscript'
status: submitted
paperurl: 'https://pratiknag.github.io/preprints/Nag_Katzfuss_NN_sparse_Cholesky_filtering.pdf'
---

**Authors:** P. Nag, M. Katzfuss

[Download paper with supplementary material (PDF)](https://pratiknag.github.io/preprints/Nag_Katzfuss_NN_sparse_Cholesky_filtering.pdf)

Filtering for high-dimensional spatio-temporal state-space models requires repeated operations with posterior covariance matrices, which is infeasible for exact Kalman filters on fine spatial grids. Nearest-neighbor Vecchia approximations are among the most accurate scalable approximations for spatial inference, but they yield sparse precision factors, whereas the forecast step of a filter requires covariances. We propose a three-stage sparse Cholesky decomposition that turns this conditional sparsity into generative sparsity. A forward-KL-optimal Vecchia factor approximates the prior precision, incomplete Cholesky factorizes the resulting sparse posterior precision, and a sparse approximate inverse recovers a sparse posterior covariance factor. The last stage decouples into small independent least-squares problems with closed-form solutions, and its objective controls the reverse KL divergence. The covariance factor gives forecast covariances and samples without any global linear solve, at quasilinear cost and in parallel; beyond filtering, it provides posterior variances and conditional simulations for other latent Gaussian models. Non-Gaussian data are handled by a Laplace approximation. In simulations with Gaussian, logistic, Poisson, and gamma data, the proposed filter is close to the exact filter, and at the same sparsity of the posterior covariance factor it is considerably more accurate than hierarchical Vecchia (HV) and low-rank filters and at least as fast as both (for 90,000 locations, about twice as fast for Gaussian data and three to five times as fast for non-Gaussian data), and, unlike HV, free of artifacts along subregion boundaries. In a filtering analysis of satellite measurements of total precipitable water vapor on a grid of 61,009 cells, the proposed filter is essentially indistinguishable from the exact Kalman filter, more accurate than HV and low-rank filters, and about three times as fast as HV and almost twice as fast as the low-rank filter.
