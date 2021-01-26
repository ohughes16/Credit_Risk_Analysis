# Credit Risk Analysis

## Overview of the analysis
I have been working on training and evaluating models with unbalanced classes for different credit risk loan approval models. This is an unbalanced classification problem as good loans outnumber risky loans. We analyzed oversampling (ROS and SMOTE) and undersampling (ClusterCentroids) the data as well as a combinatorial approach that both oversamples and undersamples (SMOTEENN) the data. We then compared two models that reduce bias, the BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. I will then provide a recommendation on whether these models should be used to predict credit risk.

## Results: The balanced accuracy scores and the precision and recall scores of all six machine learning models. 

### Random Oversampling (ROS)

- Balanced Accuracy Score

![ROS_BAS](https://user-images.githubusercontent.com/64506842/105878480-162f4e00-5fcf-11eb-889d-cc9d9b8329f8.PNG)

- Imbalanced Classification Report

![ROS_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105878461-14fe2100-5fcf-11eb-94dc-1abbc2147990.PNG)

### Synthetic Minority Oversampling Technique (SMOTE)

- Balanced Accuracy Score

![SMOTE_BAS](https://user-images.githubusercontent.com/64506842/105878462-14fe2100-5fcf-11eb-88b3-ed624a0dc5ea.PNG)

- Imbalanced Classification Report

![SMOTE_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105878463-14fe2100-5fcf-11eb-9ae7-5c17489cf535.PNG)

### Undersampling (ClusterCentroids)

- Balanced Accuracy Score

![UndersamplingCC_BAS](https://user-images.githubusercontent.com/64506842/105881700-d10d1b00-5fd2-11eb-969c-b6f42a9852de.PNG)

- Imbalanced Classification Report

![UndersamplingCC_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105881699-d10d1b00-5fd2-11eb-864d-431bc0d8e01f.PNG)

### Under and Over Sampling (SMOTEENN)

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

![EEC_BAS](https://user-images.githubusercontent.com/64506842/105887361-a2467300-5fd9-11eb-8a96-e8703a939e53.PNG)

- Imbalanced Classification Report

![EEC_imbalanced_classification_report](https://user-images.githubusercontent.com/64506842/105887362-a2df0980-5fd9-11eb-8c71-2a6e5521ef4f.PNG)

## Summary: Summary of the results of the machine learning models, recommendation on the model to use.

The above balanced accuracy scores and imbalanced classification reports for the various machine learning models are above. When deciding on which model to use to determine, we must decide what is more important with this algorithm: Do we want high precision or high sensitivity when screening loan applicants for credit risk?
