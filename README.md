# bank_credit

Business Problem
● Thera Bank is losing clients with Credit Cards service. Credit Cards services are very 
profitable due to the different fees.
● The objective of the exercise is to create a classification model that will help the bank 
improve its services so that customers do not renounce their credit cards.
● Model evaluation criterion: 
○ Model can make wrong predictions as:
○ Predicting a customer will attrite the credit card but it doesn't - Loss of resources
○ Predicting a customer will not attrite the credit card but it does - Loss of opportunity
● Which case is more important?
○ Predicting that customer will not attrite the credit card but it does is more risky for the bank because it 
loses existing customers that have relationship with the bank and the cost of engaging new 
customers is always higher than retaining old ones.
● How to reduce this loss i.e need to reduce False Negatives?
○ Company wants Recall to be maximized, greater the Recall lesser the chances of false negatives.

The Analysis is done wih Logistic Regression using the following models:
    "Decision Tree undersample tunned",
    "Random Forrest undersampled tunned",
    "AdaBoost Tuned with Grid search",
    "AdaBoost Tuned with Random search",
    "Xgboost Tuned with Grid search"
