# Kaggle-AMEX-Default-Prediction

Competition url: https://www.kaggle.com/competitions/amex-default-prediction/overview

### This repo solved the problem using the Ensemble of two LightGBMs and one XGBoost, the major efforts had spent on feature engineering.

This competition aims at developing ML models for customer credit default prediction based on a variety of customer credit card usage records, including time-series behavioral data and anonymous customer profile information provided by American Express.

Feature engineering is manipulated on the users’ historical time-series data, statistical features are added, and new features are derived such as the aggregation of numerical variables according to category variables, personalized volatility features and other personalized features. The Low-variance features are removed through the low-variance analysis.

Different versions of the model were compared and subjected to correlation analysis, and finally the average Ensemble of two LightGBMs and one XGBoost was chosen. The Ensemble model improved 0.012 on the Private Leaderboard relative to the best single model. Finally, we obtained the Private Leaderboard at 0.80776 (Top 2%).


