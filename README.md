# Coursera Practical Machine Learning Project
Coursera Practical Machine Learning Project: Prediction on Exercise Data

Ren Tu

5/16/2020

## Repository Files:
HTML assignment report: HTML_report.md

RMD assignment code: coursera_practical_ml_project.Rmd

## Executive Summary

This project draws from the fitness tracker data on six people doing exercises in 5 different ways. 

The goal is to create a classification model to predict the type of exercise done.

More information on the dataset is available here: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har

The training data for this project are available here: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The testing data for this project are available here: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

Using 52 numerical measurement variables, we produced a KNN model that achieved 100% accuracy and a near-zero p-value on the training set. 

Using this KNN model, we would expect predictions on out of sample data to have some additional error as the model may be overfitting the training data. 

However the overall accuracy on out of sample predictions should remain very high.
