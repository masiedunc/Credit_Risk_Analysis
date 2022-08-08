# Credit_Risk_Analysis

## Overview of Analysis
The purpose of this project is to create and evaluate models that predict credit risk. Credit risk has an unbalanced classification issue, so finding the right model to predict the risk for a lending company to supply loans. Using supervised learning, we trained and evaluated models and will provide a recommendation on which will best predict credit risk. 

## Results
- Naive Random Oversampling  
- SMOTE Oversampling
- Undersampling method 
- Combination over/under sampling 
  - SMOTEENN  
- Ensemble Learners
  - Balanced Random Forest Classifier
  - Easy Ensemble AdaBoost Classifier

## Summary
When evaluating all the models and methods used, it was found that many models’ low-risk categories have high precision scores of 1.00. Yet, reviewing the Oversampling and Undersampling models, lower accuracy scores were recorded. The high-risk loans are important to predict, so when we analyze the Ensemble Learners, specifically the Easy Ensemble AdaBoost Classifier, it had the best performance of all when looking at accuracy and recall scores. It is recommended to use this model for predicting credit risk. 
