# Credit_Risk_Analysis

## Overview
The purpose of this anaylsis is to evaluate three machine learning models by using resampling to determine which is better at predicting credit risk.  Oversampling will be performed using RandomOverSampler and SMOTE algorithms and undersampling will use the ClusterCentroids algorithm.  Additionally, Ensemble classifiers will be used to predict credit risk.

## Results
### RandomOverSampler
![image](https://user-images.githubusercontent.com/106352711/195679516-eec05b35-8e4f-4368-802c-7c169562b146.png)


* Balanced Accuracy Score: 0.5048920291935648
* Precison Score: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall Score: High/Low risk = 0.01/1.0

### SMOTE
![image](https://user-images.githubusercontent.com/106352711/195679882-f4a092cf-db0b-44b9-b2d5-db5ca388fe4c.png)


* Balanced Accuracy Score: 0.6628910844779521
* Precison Score: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall Score: High/Low risk = 0.63/0.69

### Undersampling
![image](https://user-images.githubusercontent.com/106352711/195680048-e3e51362-35bd-4ded-9794-a60a9d7db9b1.png)


* Balanced Accuracy Score: 0.6628910844779521
* Precison Score: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall Score: High/Low risk = 0.63/0.55

### SMOTEENN
![image](https://user-images.githubusercontent.com/106352711/195680991-17f855ba-1659-428c-a11a-fe4d2e64db41.png)


* Balanced Accuracy Score: 0.5894579694171476
* Precison Score: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall Score: High/Low risk = .72/.57

### BalancedRandomForestClassifier
![image](https://user-images.githubusercontent.com/106352711/195676550-bef71ac2-3701-4848-a19f-ca183a32d85c.png)


* Balanced Accuracy Score: 0.7885466545953005
* Precison Score: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall Score: High/Low risk = 0.70/0.87

### EasyEnsembleClassifier
![image](https://user-images.githubusercontent.com/106352711/195676658-63f9282b-d5a8-41ba-84c0-290cadf47868.png)


* Balanced Accuracy Score: 0.9316600714093861
* Precison Score: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall Score: High/Low risk = 0.92/0.94

## Summary
To predict credit risk with the given data, the EasyEnsebleClassifier had the best accurracy, over 93%.  Wheras the other models ranged in 50% to 79% accurracy. The models all had a low precision for High-risk loans and a very high precision for Low-Risk loans.
