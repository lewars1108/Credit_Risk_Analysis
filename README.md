# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to use machine learning to help Jill, a lead data scientist, to predict credit card risk. Imbalanced-learn and scikit-learn libraries will be utilized to build and evaluate models using resampling. The LendingClub, a peer-to-peer lending services company, credit card dataset was used for our model. The model will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. We will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm and compare BalancedRandomForestClassifier and EasyEnsembleClassifier machine learning models, to predict credit risk.

## Results

### Naive Oversampling

![image](https://user-images.githubusercontent.com/93399107/168494363-e0f1c66a-6297-47fc-9442-58145a51c74c.png)

### SMOTE Oversampling

![image](https://user-images.githubusercontent.com/93399107/168494621-f2116a93-dca2-4a2a-ae14-c44264ec414a.png)

### Balanced Random Forest

![image](https://user-images.githubusercontent.com/93399107/168606763-4a72b43e-6a15-4958-b62a-0b6aa69b3360.png)

## Summary

Naive oversampling had a precision score of 0.01 and recall of 0.62 for high-risk loans. The F1 score was 0.02. SMOTE oversampling had a precision score of 0.01 and recall of 0.61, and a F1 score of 0.02. The undersampling had similar results, with a precision score of 0.01, recall of 0.65, and F1 score of 0.01. Combination sampling resulted in a precision score of 0.01 and recall of 0.70, and a F1 score of 0.02. Although the recall score is better than the other models, the results are still poor. These models would not be the best models for predicting the risk of credit card applications. The random forest classifier with AdaBoost did not yield significantly better results. The precision score is 0.09 and its recall 0.92. The F1 score, again, is skewed low at 0.16 by the low precision score.In summar, the tested models would not be the most usefule models to predict our credit loan risk.
 

