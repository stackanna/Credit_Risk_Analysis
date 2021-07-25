# Credit Risk Analysis 

Comparing two new machine learning modles that reduce bias, to predict credit risk by evaluating the performance of these models. 

Click [HERE](https://github.com/stackanna/Credit_Risk_Analysis/blob/523f28b19bffd1a72c14a0153700b57812309ff4/Resources/credit_risk_ensemble.ipynb) to view [Credit Risk Analysis](https://github.com/stackanna/Credit_Risk_Analysis/blob/523f28b19bffd1a72c14a0153700b57812309ff4/Resources/credit_risk_ensemble.ipynb)

# Resources

Using machine learning to understand credit card risk. Evaluating models using imbalanced-learn and scikit-learn libraries. 

## Summary

# RandomOverSampling:

- Balance Accuracy Score: 64%
- Precision: 0.99
- Recall Score:0.62 

![alt text](https://github.com/stackanna/Credit_Risk_Analysis/blob/21384c4d6853009f1eb7b03dd4721c2a06befec8/Naive%20Random%20Oversampling.png)

# SMOTE:

- Balance Accuracy Score: 62%
- Precision: 0.99
- Recall Score: 0.69 

![alt text](https://github.com/stackanna/Credit_Risk_Analysis/blob/21384c4d6853009f1eb7b03dd4721c2a06befec8/SMOTE%20Oversampling.png)

# UnderSampling with ClusterCentoids:

- Balance Accuracy Score: 62%
- Precision: 0.99
- Recall Score: 0.41 

![alt text](https://github.com/stackanna/Credit_Risk_Analysis/blob/21384c4d6853009f1eb7b03dd4721c2a06befec8/SMOTE%20Oversampling.png)

# SMOTEEN:

- Balance Accuracy Score: 52%
- Precision: 0.99
- Recall Score: 0.58 

![alt text](https://github.com/stackanna/Credit_Risk_Analysis/blob/21384c4d6853009f1eb7b03dd4721c2a06befec8/Combination%20Over:Undersampling.png)

# Balanced Random Forest Classifier:

- Balance Accuracy Score: 78%
- Precision: 0.99
- Recall Score: 0.87 

![alt text](https://github.com/stackanna/Credit_Risk_Analysis/blob/21384c4d6853009f1eb7b03dd4721c2a06befec8/Balanced%20Random%20Forest%20Classifier.png)

# Easy Ensemble AdaBoost Classifier:

- Balance Accuracy Score: 93%
- Precision: 0.99
- Recall Score: 0.94 

![alt text](https://github.com/stackanna/Credit_Risk_Analysis/blob/21384c4d6853009f1eb7b03dd4721c2a06befec8/Easy%20Ensemble%20AdaBoost%20Classifier.png)


## Results
 Due to the low accuracy scores in the Random Oversampling, SMOTE, Undersampling, & SMOTEEN machine learning models they would not make good choices for a credit risk environment. The Balanced Random ForestClassifer & Easy Ensemble AdaBoost Classifer had much higher accuracy scores & would be the machine learning models & environments that we would reccomend to predict a credit risk analysis. 
