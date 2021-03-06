Project Topic : Credit Card Fraud Detection

Reference : DLithe

Website : www.dlithe.com

Done by: Pratheek M (4NM17CS129)

Analyzing anonymized credit card transactions labeled as fraudulent or genuine-
Figuring out the number of fraud and genuine cases in the given dataset (dataset:https://www.kaggle.com/mlg-ulb/creditcardfraud)

creditcard.csv contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

The stages involved in the project are:

i)   exploring  and analysing the nature of dataset 

ii)  Plot graphs to visualize and compare instances of fraud and genuine transactions

iii) Drawing inferences to pick any suitable algorithm to deal with the unbalanced dataset
     and figuring  out why conventional model evaluation methods fail in this case
     
iv)  Building the model and implementing  any suitable algorithm to perform
     anomaly detection
     

 Result : 30% of the given number of transaction are detected to be fraudulent with an accuracy of 90% (by using Isolation forest algorithm)
 
 
 resources and references:
1) https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html
2) https://www.analyticsvidhya.com/blog/2017/03/imbalanced-data-classification
3) https://towardsdatascience.com/handling-imbalanced-datasets-in-machine-learning-7a0e84220f28
