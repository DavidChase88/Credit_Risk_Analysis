# Credit_Risk_Analysis

## Overview of the analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we need to employ different techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will use different data sampling techniques and machine learning to predict credit risk. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models.

- Naive Random Oversampling results: Our balanced accuracy test it 65%, the precision for the high risk has a low positivity at 1% and the recall is 73%.
- SMOTE oversampling results: the accuracy score is 66%, the precision for the high risk loans has a low positvity at 1% and recall is 63% overall.
- Undersampling results: balanced accuracy score is 55% overall, the high risk precision is at 1% and the overall precision is 99% and the high risk recall is 68%.
- Combination(over and undersampling) results: balanced accuracy score is 65% the high risk precision is 1% and the overall precision is 99% and the high risk recall is 72%.
- Balanced Random Forest Classifier results: the accuracy score is 79% the high risk precision is 4% and the high risk recall is 67%.
- Easy Ensemble AdaBoost Classifier results: the accuracy score is 93% the high risk precision is 7% and the high risk recall is 91%.


## Summary

You want models with a good balance of recall and precision. ypically in your models you want a good balance of recall and precision which is why I recommend the ensemble classifiers over the first four models. The Easy Ensemble has the best balance of all the models because of it has the highest accuracy score, high-risk precision score and recall score.
