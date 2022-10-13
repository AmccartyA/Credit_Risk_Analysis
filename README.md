# Credit_Risk_Analysis

## Overview 
Since Credit risk is an inherently unbalanced classification problem, I was tasked with employing different techniques and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub,  I preformed an oversample with the data using the RandomOverSampler and SMOTE algorithms. Than I undersampled the data using a ClusterCentroids algorithm. Finally, I used two new machine learning models to reduce bias and predict credit risk.

## Results
Naive Random Oversampling results: Our balanced accuracy test it 67%, the precision for the high_risk has a very low positivity at 1% and the recall is 74%

SMOTE oversampling results: the accuracy score is 66.2%, the precision for the high_risk loans has a low positvity again at 1% and recall is 69% overall

Undersampling results: balanced accuracy score is 66.2% overall, the precision is at 99% and the recall is 41%

Combination(over and undersampling) results: balanced accuracy score is 54.7% the precision is 99% and the recall is 57% overall

Balanced Random Forest Classifier results: the accuracy score is 77.2% the precision is 99% and the recall is 88%

Easy Ensemble AdaBoost Classifier results: the accuracy score is 91.7% the precision is 99% and the recall is 94%

## Summary

When working with data, using the correct model can help determine future outcomes. With the accuracy being low on most of the models, I would keep with the ensemble classifierrs to best predict credit risk. 