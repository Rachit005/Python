Credit Card Fraud Analysis
Data Source : kaggle.com

1) The data file contains 31 attributes/variables and 2,84,807 observations.
2) There are no missing values.
3) Attribute/Variable details
    i] Time - Number of seconds elapsed between this transaction and the first transaction in the dataset.
    ii] V1 - V28 : may be result of a PCA Dimensionality reduction to protect user identities and sensitive features(v1-v28).
    iii] Amount - Transaction Amount.
    iv] Class -  1 : Fraud Transaction
                 0 : No Fraud Transaction 

4) Since the number of observations for class 1 were 492 & for class 0 were 2,84,315.
    We need to up sample the number of observations for class 1. 

5) Algorithms used are Logistic Regression, Cross Validation using Logistic Regression,Decision Tree, Bagging, KNearest Neighbors to identify the fraud transactions.

6) After upsampling the number of fraud transactions which increased the recall value of class (1) Fraud from 65% to 92% & Precision value of class (1) Fraud from 85% to 98% .

7) Used AUC-ROC metric to check the models ability to classify.
    Area Under Curve values are as follows
    Logistic Regression 95%  
    Decision Tree 99.97%
    Bagging Algorithm 100%
