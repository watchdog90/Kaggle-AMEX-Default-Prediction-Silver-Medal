# Kaggle-AMEX-Default-Prediction

Competition url: https://www.kaggle.com/competitions/amex-default-prediction/overview

This repo solve the problem using the Ensemble of two LightGBMs and one XGBoost, the major endeavour spent on feature engineering.

Feature engineering is manipulated on the users’ historical time-series data, statistical features are added, and new features are derived such as the aggregation of numerical variables according to category variables, personalized volatility features and other personalized features. The Low-variance features are removed through the low-variance analysis.



