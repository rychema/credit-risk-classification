# Module 12 Report Template

## Overview of the Analysis.

The goal is to predict if a loan is healthy or high-risk. 

The dataset was split into training and testing datasets. 

After instantiating a logistic regression model from scikit-learn, the training data was fit to the model.

Resampled training dataset was created using RandomOverSampler from imbalanced-learn.

A new logistic regression model was fit to the resampled data. 


The variables used: loan size, interest rate, borrower income, debt to income, num of accounts, derogatory marks, total debt, loan status

Data Size: 77536 rows x 8 columns 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:


Accuracy: 0.9520479254722232

Precision: 1.0 / 0.85

Recall scores: 0.99 / 0.91

Support : 18765



* Machine Learning Model 2:


Accuracy: 0.9936781215845847

Precision: 1.0 / 0.84

Recall scores: 0.99 / 0.99

Support : 18765


## Summary



The model using resampled data returned higher result at detecting healthy loan and high-risk loan alike (0.91 vs 0.99).

Model using the resampled data performs slightly better after comparing the accuracy score and classification report. 

The balanced accuracy score was higher for the resampled data (0.9937 vs 0.9520). 

The model does a really god job of predicting and classifying high-risk loans. The model is performing very well overall.

From the models both provide a high accuracy for a healthy loan, however I would choose model 2 to predict whether a loan will be healthy or not.
