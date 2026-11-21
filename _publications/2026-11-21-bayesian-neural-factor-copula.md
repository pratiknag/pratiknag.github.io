---
title: "Bayesian Neural Factor Copula Model for Spatial Data"
collection: publications
category: manuscripts
permalink: /publication/2026-11-21-bayesian-neural-factor-copula
excerpt: 'This paper proposes the Bayesian neural factor copula (BNFC), in which the common factor of a spatial factor copula is a neural network of a uniform variable and the location, so that its effect can change in strength, shape and sign over space.'
date: 2026-11-21
venue: 'Submitted manuscript'
status: submitted
paperurl: 'https://pratiknag.github.io/preprints/Nag_Gunawan_Klein_BNFC.pdf'
---

**Authors:** P. Nag, D. Gunawan, N. Klein

[Download paper with supplementary material (PDF)](https://pratiknag.github.io/preprints/Nag_Gunawan_Klein_BNFC.pdf) | [Code](https://github.com/pratiknag/Neural_factor_copula)

Factor copulas extend Gaussian process models for replicated spatial data by adding a common latent factor to a Gaussian process. The resulting copulas can be asymmetric and tail dependent, with densities that require only one-dimensional integrals. Their tail behavior is, however, fixed by a parametric factor family that must be chosen in advance, and the factor affects every location in the same way. We propose the Bayesian neural factor copula (BNFC), in which the factor is a neural network of a single uniform random variable and of the location, so that its effect can change in strength, shape and sign over space; a stationary version without the location input is a special case. The construction keeps the one-dimensional integrals, can approximate any factor distribution and, in its location-dependent form, induces factor covariances that can be any positive semidefinite matrix, so that long-range dependence may change in strength and sign over space. We characterize the tail properties of the resulting copulas and develop an approximate Bayesian inference procedure using variational Bayes for the model parameters and stochastic gradient Markov chain Monte Carlo (SG-MCMC) for the network weights. In simulations, BNFC outperforms common factor copulas, the Student-t copula, Gaussian and gamma copulas with the same spatially varying loading, and the nonparametric Bayesian transport map when the factor effect varies over space and is competitive otherwise, and in an application to daily ERA5 precipitation over central Europe the location-dependent BNFC gives the best held-out log scores and predictions of all copula models.
