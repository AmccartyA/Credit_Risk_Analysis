# Credit_Risk_Analysis
 
## Overview
Since Credit risk is an inherently unbalanced classification problem, I was tasked with employing different techniques and evaluating models with unbalanced classes. Using the credit card credit dataset from LendingClub,  I performed an oversample with the data using the RandomOverSampler and SMOTE algorithms. Then I undersampled the data using a ClusterCentroids algorithm. Finally, I used two new machine learning models to reduce bias and predict credit risk.
 
## Results
* Naive Random OverSampling: With an Accuracy score of 64.6%. The recall was 71%.
![Naive Over](https://user-images.githubusercontent.com/103524591/195484247-837b59f8-ce7b-4bac-8ec7-562d040e4372.png)

* SMOTE oversampling: the balanced score is 65.8% and recall is 68% overall
![Smote over](https://user-images.githubusercontent.com/103524591/195484259-88fa224c-f9f7-46da-9e63-d5c755af2c5b.png)

* Undersampling : The balanced score was 54.4% overall and the recall is 40%
![undersampling](https://user-images.githubusercontent.com/103524591/195484269-2b1c7817-824c-4ed5-be96-698136867312.png)

* Combination(over and under sampling): The balanced score is 64.8% and the recall is 57% overall
![combo overandunder](https://user-images.githubusercontent.com/103524591/195484281-0f4e929f-051d-49ff-bcb3-0dd485bcc1c4.png)

* Balanced Random Forest Classifier: The balanced score is 77% and the recall is 87%
![Balanced random](https://user-images.githubusercontent.com/103524591/195484296-614968e5-33cf-47d2-9a9d-ccbb85c9d5ce.png)

* Easy Ensemble AdaBoost Classifier: The balanced score is 93.2% and the recall is 94%
![easy ensemble](https://user-images.githubusercontent.com/103524591/195484303-4f866aff-f3d0-4986-8922-a99fff93c5c5.png)

## Summary
 
When working with machine learning data, using the model with the best accuracy will help determine the most likely future outcome. With the accuracy score being around 70% for all but one model. With a Score of 94%, I would reccomend we go with the Easy Ensemble AdaBoost Classifier when determining Credit Risk.
