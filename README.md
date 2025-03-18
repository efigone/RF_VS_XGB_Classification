# RF_VS_XGB_Classification
Dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

This project seeks to explore predicting customer churn and compare the performance of XGB against a classifcation RF. Upon inspection, the churned class has a heavy imbalance which was corrected using SMOTE. The data was preprocessed, and then used to train multiple XGB and RF models. Recall was used to train the models as false negatives (missing churned clients) were deemed very costly. Hyper paramters were tuned using SKlearn Grid search. The optimal model was selected by its Churn class recall performance as well as overall F1 and Precision.
