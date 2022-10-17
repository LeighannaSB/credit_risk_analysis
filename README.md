# Credit Risk Analysis

![image](https://user-images.githubusercontent.com/107161421/196074309-dc8bc927-d9d0-40ff-a05d-524aebd482c0.png)


## Overview of the analysis

- Use Resampling Models to Predict Credit Risk
- Use the SMOTEENN Algorithm to Predict Credit Risk
- Use Ensemble Classifiers to Predict Credit Risk

## Results

- **Naive Random Oversampling**
  - balanced accuracy score: 65.2%
  - precision: low for high risk loans, high for low risk loans
  - recall: high risk .62/ low risk .68
  
  ![image](https://user-images.githubusercontent.com/107161421/196072822-7d88535c-55d8-40ff-a88e-a016a4c3a9f1.png)

- **SMOTE Oversampling**
  - balanced accuracy score: 62.4%
  - precision: low for high risk loans, high for low risk loans
  - recall: high risk .59/low risk .66
  
  ![image](https://user-images.githubusercontent.com/107161421/196072974-4ef356e6-b309-40f9-b829-cbbff8414ce5.png)

- **Undersampling**
  - balanced accuracy score:51.6%
  - precision: low for high risk loans, high for low risk loans
  - recall: high risk .43/low risk .60
  
  ![image](https://user-images.githubusercontent.com/107161421/196073096-0d2e2225-7174-4ca5-a0ff-3a5f2be2ab5c.png)

- **Combination (Over and Under) Sampling**
  - balanced accuracy score: 63.8%
  - precision: low for high risk loans, high for low risk loans
  - recall: high risk .58/low risk .70
  
  ![image](https://user-images.githubusercontent.com/107161421/196073340-9e3da846-caf5-4efa-8c05-36502718c0a2.png)

- **Balanced Random Forest Classifier**
  - balanced accuracy score: 50%
  - precision: low for high risk loans, high for low risk loans
  - recall: high risk 0/low risk 100
  
  ![image](https://user-images.githubusercontent.com/107161421/196073530-ca5215e2-feb1-4426-b6cf-3c6031653226.png)

- **Easy Ensemble AdaBoost Classifier**
  - balanced accuracy score: 92.5%
  - precision: low for high risk loans, high for high risk loans
  - recall: high risk .91/low risk .94
  
  ![image](https://user-images.githubusercontent.com/107161421/196073663-6fc0771c-b866-48ba-81ae-9b226eff07de.png)


## Summary

Accross the board each model yielded very low precision for high risk loans and very high precision for low risk loans while the accuracy score varied from model to model. The Easy Emsemble model produced the highest accuracy so it would be recommended if any of the tested models were to be used however, this model did still have low precision on high risk loans so ultimately further analysis would be recommended in order to build a model with better precision on high risk loans. 
