# Credit_Risk_Analysis

## Overview: 
The purpose of this analysis is to apply machine learning to predict credit card risk using the credit card credit dataset from LendingClub. Through different techniques we had to train and evaluate models with unbalanced classes and build and evaluate models using resampling. We oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. We then used the SMOTEENN algorithm for combination sampling. Finally, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results: 

### Oversampling with RandomOverSampler
- Balanced Accuracy Score: 0.65 
- Precision Score: 0.99
- Recall Score: 0.59

<img width="784" alt="Screen Shot 2021-05-30 at 5 37 31 PM" src="https://user-images.githubusercontent.com/77817870/120125550-2f5b2d80-c16e-11eb-938e-b3c004f85b68.png">

### Oversampling with SMOTE
- Balanced Accuracy Score: 0.66
- Precision Score: 0.99
- Recall Score: 0.69

<img width="783" alt="Screen Shot 2021-05-30 at 5 42 11 PM" src="https://user-images.githubusercontent.com/77817870/120125634-76e1b980-c16e-11eb-9e67-b3bc35621739.png">

### Undersampling with ClusterCentroids
- Balanced Accuracy Score: 0.54 (Lowest balanced accuracy score of all models)
- Precision Score: 0.99
- Recall Score: 0.40 (Lowest recall score of all models)

<img width="789" alt="Screen Shot 2021-05-30 at 5 44 36 PM" src="https://user-images.githubusercontent.com/77817870/120125728-c3c59000-c16e-11eb-85e8-c36846f36bc9.png">

### Combination Sampling with SMOTEENN
- Balanced Accuracy Score: 0.66
- Precision Score: 0.99
- Recall Score: 0.61

<img width="774" alt="Screen Shot 2021-05-30 at 5 47 06 PM" src="https://user-images.githubusercontent.com/77817870/120125847-21f27300-c16f-11eb-9442-ffe8a07b192e.png">

### Machine Learning with BalancedRandomForestClassifier
- Balanced Accuracy Score: 0.79
- Precision Score: 0.99
- Recall Score: 0.87

<img width="773" alt="Screen Shot 2021-05-30 at 5 52 49 PM" src="https://user-images.githubusercontent.com/77817870/120126061-e4421a00-c16f-11eb-824d-58c8a206b585.png">

### Machine Learning with EasyEnsembleClassifier
- Balanced Accuracy Score: 0.93 (Highest balanced accuracy score of the machine learning models)
- Precision Score: 0.99
- Recall Score: 0.94 (Highest recall score of the machine learning models)

<img width="779" alt="Screen Shot 2021-05-30 at 5 54 18 PM" src="https://user-images.githubusercontent.com/77817870/120126131-18b5d600-c170-11eb-9b7b-4f67f5cf60fb.png">

## Summary: 
In summary, the machine learning model that performed the best was EasyEnsembleClassifier. This model had the highest balanced accuracy and recall score of all models. The machine learning with the worst performance is ClusterCentroids. This model had the lowest balanced accuracy and recall score of all models. The rest of the models did not have stellar performance, and would not be recommended to use. The model recommended to use would be the EasyEnsembleClassifier because it has the best balanced accuracy score and the imbalanced classification report shows totals greater than 0.87 or 87%.  
