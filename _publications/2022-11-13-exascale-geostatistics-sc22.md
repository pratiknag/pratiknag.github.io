---
title: "Reshaping Geostatistical Modeling and Prediction for Extreme-Scale Environmental Applications"
collection: publications
category: manuscripts
permalink: /publication/2022-11-13-exascale-geostatistics-sc22
excerpt: 'This paper extends space-time geostatistical modeling using mixed-precision and low-rank algebraic approximations at extreme scale.'
date: 2022-11-13
venue: 'SC22: International Conference for High Performance Computing, Networking, Storage and Analysis'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10046053/'
---

**Authors:** Q. Cao, S. Abdulah, R. Alomairy, Y. Pei, P. Nag, G. Bosilca, J. Dongarra, M. G. Genton, D. E. Keyes, H. Ltaief, Y. Sun

We extend the capability of space-time geostatistical modeling using algebraic approximations, illustrating application-expected accuracy worthy of double precision from majority low-precision computations and low-rank matrix approximations. We exploit the mathematical structure of the dense covariance matrix whose inverse action and determinant are repeatedly required in Gaussian log-likelihood optimization. Geostatistics augments first-principles modeling approaches for the prediction of environmental phenomena given the availability of measurements at a large number of locations; however, traditional Cholesky-based approaches grow cubically in complexity, gating practical extension to continental and global datasets now available. We combine the linear algebraic contributions of mixed-precision and low-rank computations within a tile based Cholesky solver with on-demand casting of precisions and dynamic runtime support.
