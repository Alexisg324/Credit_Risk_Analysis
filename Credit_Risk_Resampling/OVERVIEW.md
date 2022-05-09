# Module 12 Report Template

## Overview of the Analysis

This analysis uses logistic regression to predict the accuracy and precision of a predicted model.  

The analysis uses the users lending history and predicts if the user is fit in credit history via Unutilized Supervised ML.  

The x and y represent the split data that determines the users credit health. 
y = loan_status
X = value_counts

In order to analyze the data, the csv files are read as a DateFrame; (X, y) are used as values and labels, the data is then split between with logistic regression.  
Two models are formed (0 and 1) 0 = inital data and 1 = oversampled data)

Methods used include RandomOverSampler & Logistic Regression.

## Results

Balanced accuracy scores and the precision and recall scores of all machine learning models 1 & 2:

* Machine Learning Model 1:
Healthy loan: is 100% accuracy with a model prediction of 1.00.
High-Risk loan: is 85 % for accurate prediction, so likely to classify high risk loans inaccurately 15% of the time.


* Machine Learning Model 2:
Healthy Loan: Prediction is 100% accurate, with a model of 1.00. High-risk Loan: Prediction is due 84% accurate, so 16% likely to be inaccurate.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
Both of the learning models have high accuracy however model 2 had an innacuracy score of 16%, which is more than model 1.  
