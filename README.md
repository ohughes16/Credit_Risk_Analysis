# Credit Risk Analysis

## Overview of the analysis
I have been working on training and evaluating models with unbalanced classes for different credit card risk approval models. We analyzed oversampling (ROS and SMOTE) and undersampling(ClusterCentroids) the data as well as a combinatorial approach that both oversamples and undersamples (SMOTEENN) the data. We then compared two models that reduce bias, the BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. I will then provide a recommendation on whether they should be used to predict credit risk and the 

## Results: The balanced accuracy scores and the precision and recall scores of all six machine learning models. 

### Random Oversampling 

- Balanced Accuracy Score
![ROS_BAS](https://user-images.githubusercontent.com/64506842/105878480-162f4e00-5fcf-11eb-889d-cc9d9b8329f8.PNG)

- Imbalanced Classification Report
![ROS_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105878461-14fe2100-5fcf-11eb-94dc-1abbc2147990.PNG)

### SMOTE

- Balanced Accuracy Score
![SMOTE_BAS](https://user-images.githubusercontent.com/64506842/105878462-14fe2100-5fcf-11eb-88b3-ed624a0dc5ea.PNG)

- Imbalanced Classification Report
![SMOTE_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105878463-14fe2100-5fcf-11eb-9ae7-5c17489cf535.PNG)

### Undersampling (ClusterCentroids)

- Balanced Accuracy Score
![Undersampling_BAS](https://user-images.githubusercontent.com/64506842/105878464-14fe2100-5fcf-11eb-97e5-1e02ecb5b5b9.PNG)

- Imbalanced Classification Report
![Undersampling_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105878466-1596b780-5fcf-11eb-808e-b3d6bfe68a53.PNG)

### Under and Over Sampling (SOTEENN)

- Balanced Accuracy Score
![Combination_BAS](https://user-images.githubusercontent.com/64506842/105878472-1596b780-5fcf-11eb-85ed-32e198abee1a.PNG)

- Imbalanced Classification Report
![Combination_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105878473-1596b780-5fcf-11eb-8fc8-25b0a72fdd44.PNG)

### Balanced Random Forest Classifier

- Balanced Accuracy Score
![BalancedRandomForest_BAS](https://user-images.githubusercontent.com/64506842/105878469-1596b780-5fcf-11eb-9c7e-faa2fdfbee99.PNG)

- Imbalanced Classification Report
![BalancedRandomForest_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105878471-1596b780-5fcf-11eb-8755-6b1fb0e51e3b.PNG)

### Easy Ensemble Classifier

- Balanced Accuracy Score
![EEC_BAS](https://user-images.githubusercontent.com/64506842/105878477-162f4e00-5fcf-11eb-9653-6337448ce6c6.PNG)

- Imbalanced Classification Report
![EEC_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105878478-162f4e00-5fcf-11eb-982e-fe9b72c5bb34.PNG)

## Summary: Summary of the results of the machine learning models, recommendation on the model to use.


