# Module 20 Report

## Overview of the Analysis

For this challenge we could apply many techniques to instantiate, to fit and to evaluate two models based on the dataset information about loan risk

* The purpose of the analysis is to find out wich model performs better and compare the results to make better predictions
* We look out for the risk level on the loans and which ones are worthy of investment.

* For the machine learning process the stages of this analysis are the creation of labels and features of the data structure, the data split training and the testing of the datasets, the model creation with the adjustments for the fitting, the calculation of predicctions and finally the model evaluation and report

* There were two methods used for this analysis, first one was the Linear model with Logistic Regreesion classifier and the Random over sampling with Logistic Regression classifier.

## Results


* Machine Learning Model 1: Logistic Regression with imbalanced dataset
  * Description of Model 1 Accuracy: 0.944
  * Precision: Label 0 :1.00 // Label 1: 0.87
  * Recall scores: Label 0: 1.00 // Label 1: 0.89



* Machine Learning Model 2: Logistic Regression sampled
  * Description of Model 2 Accuracy: 1.00
  * Precision: Label 0 : 1.00 // Label 1: 0.99
  * Recall scores:Label 0 : 0.99 // Label 1 : 1.00

## Summary
For this challenge, we used a dataset containinig information about lending services for the risk evaluation, from building two models it is possible to compare the results and find out wich model performs better 
*The first  meodel shows  a good performance whit class 0  but for class 1 it is lower .
* Second model has a better performance with both classes so this Logistic Regression model is better to make the necessary predictions sinxec it is fitted with random over-sampled data.

