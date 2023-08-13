# Credit_card_fraud_detection-Project
Credit Card Fraud Detection using Logistic Regression on credit card dataset

# About Dataset
Since the size of the dataset is 150 MB, therefore I am adding the link of kaggle dataset
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive
class (frauds) accounts for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Features V1, V2, … V28 are the principal components obtained with PCA, 
the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first
transaction in the dataset.
The feature 'Amount' is tthis feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in 
case of fraud and 0 otherwise.
