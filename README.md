# Module 20 Credit Risk Analysis Challenge
The goal of this challenge us to show my ability to use various techniques to train and evaluate a model based on loan risk. This challenge will utilize a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The Jupyter Notebook documenting the process of building the supervised learning model is located in [here](credit_risk_classification.ipynb)

# Credit Risk Analysis Report

## Model 1 regression

**Question:** How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** The <strong style="color: red;">100% prediction of low-risk loans</strong> from the Logistic Regression model is encouraging. The <strong style="color: blue;">high-risk loans on the other hand is encouraging enough at 89%</strong>, although if I was a loan officer, I'd still proceed with a heaothy dose of caution. 

## Model 2 Regression with Randon Over Sample module
**Question:** How well does the logistic regression model, fit with oversampled data, predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** The logistic regression model fitted with oversampled data performs <strong style="color: blue;">exceptionally well in predicting both healthy (0) and high-risk (1) loans</strong>. The perfect recall (1.00) for both classes indicates that the model is excellent at identifying all true cases of each class. The precision for <strong style="color: red;">high-risk loans is slightly lower (0.87), suggesting some misclassification of healthy loans as high-risk but is still quite high</strong>. The model shows a strong capability to distinguish between healthy and high-risk loans, making it a powerful tool for this specific classification task.