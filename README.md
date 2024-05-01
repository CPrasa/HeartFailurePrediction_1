# Heart Failure Prediction

![Heart Failure](https://github.com/CPrasa/Heart-Failure-Prediction/assets/121708803/75d2c103-399a-4e64-8cf5-a8c8eb2e4134)

## Overview
This project aims to predict heart failure using logistic regression, leveraging a dataset sourced from Kaggle. The dataset contains vital health-related features of individuals, and through logistic regression, we determine the likelihood of heart disease occurrence. Additionally, we explore the dataset, preprocess it to handle missing values, visualize key insights, apply encoding and normalization techniques, and perform hyperparameter tuning to optimize model performance. Moreover, we compare the effectiveness of logistic regression with the random forest algorithm to identify the best predictive approach.

## Dataset
The dataset (`heart.csv`) comprises 918 instances and encompasses a range of health indicators. Each data point provides valuable information for predicting the presence or absence of heart disease.

## Preprocessing
Before model training, we preprocess the data. This involves handling missing values, ensuring consistency, and preparing the dataset for analysis. Missing data is addressed using appropriate techniques to maintain data integrity.

## Visualization
Data visualization is employed to gain insights into the dataset's characteristics. Visual representations aid in understanding feature distributions, correlations, and potential patterns, contributing to better model selection and interpretation.

## Encoding
Categorical variables are encoded to facilitate model training. This transformation ensures compatibility with the chosen machine learning algorithms, enhancing the accuracy and efficiency of predictions.

## Normalization
Feature normalization is performed to standardize the scale of input variables. This step optimizes model convergence and improves performance, particularly for algorithms sensitive to feature magnitudes.

## Hyperparameter Tuning
Optimizing model parameters is crucial for achieving the best predictive performance. Hyperparameter tuning techniques are applied to fine-tune model settings, enhancing predictive accuracy and generalization ability.

## Model Comparison
We evaluate the effectiveness of logistic regression and random forest algorithms for heart failure prediction. By comparing their performance metrics, including accuracy, precision, recall, and F1-score, we determine the most suitable algorithm for this task.

Through these steps, we aim to develop a reliable heart failure prediction model that can assist healthcare professionals in early detection and intervention, potentially saving lives and improving patient outcomes.
