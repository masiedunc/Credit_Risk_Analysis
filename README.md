# Credit_Risk_Analysis

## Overview of Analysis
The purpose of this project is to create and evaluate models that predict credit risk. Credit risk has an unbalanced classification issue, so finding the right model to predict the risk for a lending company to supply loans. Using supervised learning, we trained and evaluated models and will provide a recommendation on which will best predict credit risk. 

## Results
### Naive Random Oversampling

![Naive Random Sampling](https://user-images.githubusercontent.com/102122063/183328168-377b9bd1-c289-4060-b7e6-870681d078e1.PNG)

  - The Naive Random Oversampling model results:
    - Balanced accuracy score of 0.6636
    - High-risk precision score of 0.01
    - High-risk recall score of 0.70
    - Low-risk precision score of 1.00
    - Low-risk recall score of 0.62.
-----

### SMOTE Oversampling

 - The SMOTE Oversampling model results:
    - Balanced accuracy score of 0.6622
    - High-risk precision score of 0.01
    - High-risk recall score of 0.63
    - Low-risk precision score of 1.00
    - Low-risk recall score of 0.69
-----

### Undersampling
 
![under sampling](https://user-images.githubusercontent.com/102122063/183328191-2107f180-7ae7-463f-9d32-ca4deb766d07.PNG)

- The Undersampling model results:
    - Balanced accuracy score of 0.5447
    - High-risk precision score of 0.01
    - High-risk recall score of 0.69
    - Low-risk precision score of 1.00
    - Low-risk recall score of 0.40
 -----
 
### SMOTEEN Combination over/under sampling 

![Combination sampling](https://user-images.githubusercontent.com/102122063/183328234-93fa7f42-5241-4d38-b8cf-130e8f82d1c7.PNG)

  - SMOTEEN Combination over/under sampling model results:
    - Balanced accuracy score of 0.6447
    - High-risk precision score of 0.01
    - High-risk recall score of 0.72
    - Low-risk precision score of 1.00
    - Low-risk recall score of 0.57 
 -----
 
### Ensemble Learners
  - Balanced Random Forest Classifier
  
 ![random forest](https://user-images.githubusercontent.com/102122063/183329005-b4bc31ae-871e-4c99-82e0-b53217ad56c2.PNG)

  - Easy Ensemble AdaBoost Classifier
  
![Ada Boost](https://user-images.githubusercontent.com/102122063/183329036-fd644859-5d19-437f-8ad0-777c67b8cc52.PNG)


## Summary
When evaluating all the models and methods used, it was found that many models’ low-risk categories have high precision scores of 1.00. Yet, reviewing the Oversampling and Undersampling models, lower accuracy scores were recorded, with Undersampling having the lowest scores. The high-risk loans are important to predict, so when we analyze the Ensemble Learners, specifically the Easy Ensemble AdaBoost Classifier, it had the best performance of all when looking at accuracy and recall scores. It is recommended to use this model for predicting credit risk. 
