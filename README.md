# credit-risk-classification
Module 20 Challenge

Resources: 
Xpert Learning Assistant
Assistance with Confusion Matrix from Amanda Lor


## Overview

The purpose of this analysis was to create a confusion matrix based off of a logistic regression model to evaluate the performance and predict loan health based on financial information, such as loan size, interest rate,  total debt, borrowwer income, derogatory marks and accounts. The main steps to achieve this, was by creating a logistic regression model, by using LogisticRegression, and then splitting the data on X and Y, using train_test_split. I then fit the data into the logistic regression model to run predictions. Based off of the predictions, a confusion matrix was created, by using confusion_matrix, and inputting the predictions into the model. 


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Accuracy: 99%
    * Precision: 
        * Class 0: 1.00
        * Class 1: 0.84
    * Recall: 
        * Class 0: 0.99
        * Class 1: 0.94


## Summary


The machine learning model showed a strong performance with an accuracy rate of 99%, however due to the dataset's imbalance, the model's efficiency can be affected. For best results, the use of of a random forest classifier should be used, as it can predict high-risk loans accurately for financial decision-making, with high performance in recall and precision.