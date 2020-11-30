# Credit_Risk_Analysis
## Overview of the Analysis
In this analysis we are comparing six different sampling models in order to predict the credit risk on credit cards loans. And we will choose the one or if none of this models is suitable for credit card risk prediction.
## Results

<img width="712" alt="RandomUnderSampler" src="https://user-images.githubusercontent.com/68616522/100560370-95c8c700-3283-11eb-862f-c7462e71e4ce.png">
* The Random User Sampler has a balanced accuracy score of about 57%. The high risk precision is 1% with a sensitivity of 62%. The low risk precision is  100% with a sensitivity of 53%.

<img width="713" alt="SMOTE" src="https://user-images.githubusercontent.com/68616522/100560373-97928a80-3283-11eb-89c4-9700d0815ef3.png">
* The SMOTE has a balanced accuracy score of about 65%. The high risk precision is 1% with a sensitivity of 61%. The low risk precision is 100% with a sensitivity of 69%.

<img width="709" alt="ClusterCentroids" src="https://user-images.githubusercontent.com/68616522/100560383-99f4e480-3283-11eb-83d1-4383e5075fb9.png">
The ClusterCentroids has a balanced accuracy score of about 54%. The high risk precision is 1% with a sensitivity of 67%. The low risk precision is 100% with a sensitivity of 42%.

<img width="708" alt="SMOTEEN" src="https://user-images.githubusercontent.com/68616522/100560393-9eb99880-3283-11eb-93a4-32d6d50544a5.png">
The SMOTEEN has a balanced accuracy score of about 64%. The high risk precision is 1% with a sensitivity of 72%. The low risk precision is 100% with a sensitivity of 57%.

<img width="710" alt="BalancedRandomForestClassifier" src="https://user-images.githubusercontent.com/68616522/100560396-a1b48900-3283-11eb-92ba-f7f334064d4b.png">
The Balanced Random Forest Classifier has a balanced accuracy score of about 79%. The high risk precision is  3% with a sensitivity of 70%. The low risk precision is 100% with a sensitivity of 87%.

<img width="714" alt="EasyEnsembleClassifier" src="https://user-images.githubusercontent.com/68616522/100562348-6e74f880-3289-11eb-9d9d-cfe7189d9340.png">
The Easy Ensemble Classifier has a balanced accuracy score of about 93%. The high risk precision is 9% with a sensitivity of 92%. The low risk precision is 100% with a sensitivity of 94%.

## Summary
After comparing these 6 models I recommend using the Easy Ensemble Classifier since it is the one that give us the best balanced accuracy score (93%). Eventhough, it is the one with the best precission to predict high risk; I do recommend not to use this model in order to predict high risk loans since its precision for it is just 4%. The model should be used to predict low risk loans in order to approve loans.
