# Rainfall-Prediction-using-Machine-Learning

## Overview
This project focuses on predicting rainfall using various machine-learning algorithms. The goal is to develop a model that can accurately forecast rainfall based on Australian weather data. The project involves data preprocessing, model training, and evaluation.

## Dataset
The dataset used for this project includes historical weather data such as temperature, humidity, wind speed, pressure, and location. The dataset can be obtained from https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

## Features
Binary classification model to predict whether it will rain or not the next day.
Implemented algorithms: Logistic Regression, KNN, Decision Tree, Random Forest, ExtraTrees, GaussainNB, Catboost, XGBoost, GradientBoost, lightgbm, AdaBoost, VotingClassifier.
Implemented hyperparamter tuning via GridSearchCV
Utilized KFold Cross-Validation for validation of the model
The evaluation of the model is done on Accuracy(86.2%),  roc_auc(88.08%).
