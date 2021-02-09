# Supervised Machine Learning and Credit Risk Analysis

## Overview of Analysis
The purpose of this analysis is to predict credit risk using machine learning algorithms. The strengths and weaknesses of machine learning models were assessed throughout the analysis. 

- RandomOverSampler and SMOTE algorithms were used to oversample the data. 
- The ClusterCentroids algorithm was used to undersample the data. 
- The SMOTEEN algorithm was used for a combinational approach of over and undersampling. 
- BalancedRandomForestClassifier and EasyEnsembleClassifier were utilized to predict credit risk. 

## Results

### Naive Random Oversampling results: 
- The balance accuracy score was 66% which is low.
- The precision for high_risk was 1%, which denoteslow positivity. The recall was 66%.

### SMOTE Oversampling results:
- Balance accuracy score was about 63% which is considered low.
- The precision for high_risk was 1% which denotes low positivity. The recall was 61%.

### Undersampling ClusterCentroids results:
-Balance accuracy score was 52% which is low.
-The precision for low_risk was 99% which is very high. The recall was 40%.

### Combination Sampling With SMOTEENN results:
-Balance accuracy score was 64% which is low.
-The precision for low_risk was 99% which is very high. The recall was 57%.


### Balanced Random Forest Classifier results:
-Balance accuracy score was 79%.
-The precision for low_risk was 99% which is very high. The recall was 91%.

### Easy Ensemble AdaBooster Classifier results:
-Balance accuracy score was 93% which is high.
-The precision for low_risk was 99% which is very high. The he recall was 94%.

## Summary 
Based on the results, Easy Ensemble was the best performance model to predict credit risk. This is due to its recall score, high balanced accuracy score, and high precision score. 
