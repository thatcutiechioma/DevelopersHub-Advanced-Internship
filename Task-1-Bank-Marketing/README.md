# Task 1: Term Deposit Subscription Prediction

## Objective
Predict whether a bank customer will subscribe to a term deposit as a result of a marketing campaign.

## Dataset
Bank Marketing Dataset (UCI Machine Learning Repository)

## Approach
- Loaded and explored the dataset
- Encoded categorical features using one-hot encoding
- Trained Logistic Regression and Random Forest models
- Evaluated models using Confusion Matrix, F1-Score, and ROC Curve
- Used SHAP to explain model predictions

## Results & Insights
- Random Forest performed better than Logistic Regression
- Campaign duration, balance, and previous outcomes strongly influenced subscription decisions
- SHAP improved model interpretability and trust
