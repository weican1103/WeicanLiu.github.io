---
title: "Cnns-transformer based day-ahead probabilistic load forecasting for weekends with limited data availability"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'I am the second author'
date: 2024-2-12.
venue: 'Energy(JCR Q1)'
citation: 'Tian, Z., Liu, W., Jiang, W., & Wu, C. (2024). Cnns-transformer based day-ahead probabilistic load forecasting for weekends with limited data availability. Energy, 293, 130666.'
---

Independent system operators (ISOs) are pursuing day-ahead probabilistic load forecasting as it offers comprehensive load trend and pattern information. Compared with commonly adopted point forecasting, it enables ISOs to better understand the uncertainty of future demand through interval forecasting with varying confidence levels. In practice, this advantage could enable precise day-ahead forecasting for critical days with irregular load patterns (e.g., weekends or holidays), particularly when the data availability is limited. To this end, we customize a day-ahead probabilistic load forecasting framework with an emphasis on weekends based on data processing and probabilistic deep learning. Specifically, data processing combines data denoising and data augmentation techniques, incorporating peak and trend information into the denoised one-dimensional time series data to aid training. This procedure helps extract more information from the restricted training samples. The probabilistic deep learning, CNNs-Transformer, combines multi-layer Convolutional Neural Networks and Transformer, adopting QRLoss (quantile regression loss function) to achieve probabilistic forecasting. The loss penalty technique enhances the model’s attention to weekend data. Numerical studies based on field data suggest that the proposed framework can obtain accurate day-ahead probabilistic forecasting results (48-time points of the whole day) by using only two-week historical data, and the accuracy improvement over its rivals is remarkable on weekends.
