---
title: Real-World Applications
summary: When applying probabilistic models to real-world problems, data complexities such as non-stationarity and heteroscedasticity can significantly degrade model performance and lead to unreliable uncertainty estimates. Non-stationarity arises when statistical properties vary across the input space, while heteroscedasticity reflects non-uniform noise levels in different regions. Therefore, it is essential to design probabilistic models and inference algorithms that explicitly handle these challenges so that the resulting systems remain robust, interpretable, and trustworthy in practical applications.
show_date: false
image:
  preview_only: true
weight: 4
---


- **[Subseasonal climate forecasting](/publication/2-jounrnal-gp-mjo/)** develops a probabilistic framework
for <a href="https://en.wikipedia.org/wiki/Madden%E2%80%93Julian_oscillation" style="color:blue;">Madden-Julian Oscillation</a> (MJO) prediction based on GP models with empirical correlations and a covariance correction, extending probabilistic MJO coverage to over three weeks. Additionally, the method avoids the need for hyperparameter optimization, streamlining the process and enhancing efficiency and stability

- **[Privacy-aware regression](/publication/5-journal-privacy-aware-gp/)** develops a comprehensive theoretical and methodological framework for privacy-aware Gaussian process regression that addresses the fundamental privacy-utility trade-off inherent in predictive modeling with confidential data. The proposed method enforces variance-based privacy guarantees by solving for an optimal synthetic noise covariance via semi-definite programming, so GP predictors stay accurate yet satisfy the prescribed privacy level in settings such as satellite tracking and census analytics.