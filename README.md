# Predict_Bank_Customer_Churn
Comparison of Churn Classification models using Ensemble methods

## Introduction
This churn modeling notebook is associated with focused customer retention programs, i.e. predict behavior to retain customers and uses a bank's churning dataset to build a classifier for predicting customer churn. The data set is obtained from Kaggle. The goal is to predict whether a bank customer will churn or not, that is, whether the customer will leave the bank (close account) or continue to be a customer given customer details.

For this task, different ensemble methods are compared for the binary classification modeling. An ensemble is a composite modeling that combines few low performing classifiers to create an improved classifier. In particular the models employed are:

1. Voting (Hard and Soft)
2. Bagging
3. Boosting (AdaBoost, XGBoost, LightGBM)
4. Stacking

The performance metrics used is accuracy.

## Result
Overall, for the data provided, Boosting technique shows highest accuracy to predict customer churn and Bagging shows the least. Stacking accuracy(0.851) is somewhat close and comparable to Boosting-LGBM results(0.852). Individually, Random Forest accuracy score is the highest overall at 0.8535.
