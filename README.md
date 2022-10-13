# Credit_Risk_Analysis
 
## Overview
Since Credit risk is an inherently unbalanced classification problem, I was tasked with employing different techniques and evaluating models with unbalanced classes. Using the credit card credit dataset from LendingClub,  I performed an oversample with the data using the RandomOverSampler and SMOTE algorithms. Then I undersampled the data using a ClusterCentroids algorithm. Finally, I used two new machine learning models to reduce bias and predict credit risk.
 
## Results
Naive Random OverSampling: With an Accuracy score of 64.6%. The precision for the high_risk has a very low positivity, about 1% and the recall was 71%.
 
SMOTE oversampling: the balanced score is 65.8%, the precision for the high_risk loans has a low positivity again at 1% and recall is 68% overall
 
Undersampling : The balanced score was 54.4% overall and the recall is 40%
 
Combination(over and under sampling): The balanced  score is 64.8%  and the recall is 57% overall
 
Balanced Random Forest Classifier: The balanced score is 77% and the recall is 87%
 
Easy Ensemble AdaBoost Classifier: The balanced score is 93.2% and the recall is 94%
 
## Summary
 
When working with machine learning data, using the model with the best accuracy will help determine the most likely future outcome. With the accuracy being low on most of the models, I would keep with the Easy ensemble classifiers to best predict credit risk.
