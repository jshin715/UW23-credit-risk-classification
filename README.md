# UW23-credit-risk-classification

## Credit Risk Analysis Report

Overview:   
Using a dataset of historical lending activity from a peer-to-peer lending services company, we are building a model that can identify the creditworthiness of borrowers.   
A logistic regression model is used to train and evaluate based on loan risk.

Machine Learning Model (Logistic Regression) Results:   
  * accuracy score : 99%
  * precision score : 100% (healthy), 85% (high-risk)
  * recall score : 99% (healthy), 91% (high-risk)

Summary:   
For 0 (healthy loan), there is 100% precision and 99% recall rate. When a loan is predicted as healthy, it is correct 100% of the time and the model identifies 99% of the healthy loans.

For 1 (high-risk loan), there is 85% precision score and 91% recall. 85% of the predicted high risk loans are correctly predicted as high risk. 91% of the high risk loans are correctly predicted as high-risk. 9% of high-risk loans are missed by the model's predictions.

This model is great at identifying healthy loans and this model is better at identifying healthy loans than high-risk. This model is recommended for use, but has room for improvement when identifying high-risk loans.
