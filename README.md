# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to use machine learning to help Jill, a lead data scientist, to predict credit card risk. Imbalanced-learn and scikit-learn libraries will be utilized to build and evaluate models using resampling. The LendingClub, a peer-to-peer lending services company, credit card dataset was used for our model. The model will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. We will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm and compare BalancedRandomForestClassifier and EasyEnsembleClassifier machine learning models, to predict credit risk.

## Results

## Summary

The random forest classifier, with and without AdaBoost, failed to achieve useable performance. The balanced random forest classifier's precision is 0.04, meaning that in 100 loan applications that were flagged to be bad, only 4 were actually bad loan applications. The model's recall/sensitivity is 0.67, meaning that it detected 67% of bad loan applications. The F1 score is low at 0.07, since either a low precision or recall will result in a lower F1 score.The random forest classifier with AdaBoost, while achieving better results, still suffered from inadequate predictive power. Its precision score is 0.09 and its recall 0.92. The F1 score, again, is skewed low at 0.16 by the low precision score.The performances of both models are insufficient for commercial application.
