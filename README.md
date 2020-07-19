# Credit Card Fraud Detection

This notebook is my solution to the Credit Card Fraud Detection Kaggle Challenge which can be found [here](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## Abstract
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
The challenge is to build a predictive model that can identify fraudulent credit card transactions. 

## Workflow

Preliminary data analysis showed the dataset is highly imbalanced with **284315** authentic entries and only **492** fraudlent entries. 

To handle this imbalanced data I've used *SMOTE* from **imblearn** module to reduce the imbalance.

After balancing the data I've used a neural network model to make the predictions. 

## Conclusion

My final submission gave me a roc_auc_score of **0.99**.
