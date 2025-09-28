---
title: "Spatio-temporal DeepKriging for interpolation and probabilistic forecasting, Spatial Statistics "
collection: publications
category: manuscripts
permalink: /publication/2023-09-27-paper-title-number-2
excerpt: 'This paper devises a novel nonparametric approach for prediction of complex spatio-temporal phenomena.'
date: 2023-09-27
venue: 'Spatial Statistics'
paperurl: 'https://doi.org/10.1016/j.spasta.2023.100773'
---

Gaussian processes (GP) and Kriging are widely used in traditional spatio-temporal modelling and prediction. These techniques typically presuppose that the data are observed from a stationary GP with a parametric covariance structure. However, processes in real-world applications often exhibit non-Gaussianity and nonstationarity. Moreover, likelihood-based inference for GPs is computationally expensive and thus prohibitive for large datasets. In this paper, we propose a deep neural network (DNN) based two-stage model for spatio-temporal interpolation and forecasting. Interpolation is performed in the first step, which utilizes a dependent DNN with the embedding layer constructed with spatio-temporal basis functions. For the second stage, we use Long-Short Term Memory (LSTM) and convolutional LSTM to forecast future observations at a given location. We adopt the quantile-based loss function in the DNN to provide probabilistic forecasting. Compared to Kriging, the proposed method does not require specifying covariance functions or making stationarity assumptions and is computationally efficient. Therefore, it is suitable for large-scale prediction of complex spatio-temporal processes. We apply our method to monthly PM2.5 data at more than 200,000 space–time locations from January 1999 to December 2022 for fast imputation of missing values and forecasts with uncertainties.
