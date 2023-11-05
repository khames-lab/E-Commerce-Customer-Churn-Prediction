# E-commerce Churn Prediction

## Overview
This project focuses on predicting customer churn for an e-commerce platform. Churn prediction is a crucial task for businesses to understand and retain customers. This project involves data analysis, preprocessing, modeling, and interpretability techniques to develop an effective churn prediction model.

## Table of Contents
- [Dataset](#dataset)
- [Data Analysis](#data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Model Evaluation](#model-evaluation)
- [Model Interpretability](#model-interpretability)
- [Usage](#usage)

## Dataset
The dataset used in this project is obtained from the e-commerce platform's records. It includes customer information, purchase history, engagement data, and a churn label (churned or not). The dataset is used for training and evaluating the churn prediction model.

## Data Analysis
The project begins with data analysis, where we explore the dataset to understand its structure. This includes examining the shape, columns, data types, and summary statistics of the dataset. We also analyze the distribution of churned and non-churned customers.

![2](https://github.com/khames-lab/E-Commerce-Customer-Churn-Prediction/assets/77197337/80a6cc1b-59ee-4069-b4b4-e40e8bc07ffa)

## Data Preprocessing
Data preprocessing involves several steps:
- Handling missing values in the dataset.
- Encoding categorical variables.
- Feature engineering to create new features from existing data.
- Handling class imbalance if present.
- Splitting the data into training and testing sets.

## Modeling
The project implements and evaluates various machine learning models for churn prediction, including:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting (e.g., XGBoost)

The models are trained to predict customer churn based on the dataset's features.

## Model Evaluation
The models' performance is evaluated on a test dataset. Metrics like accuracy, precision, recall, F1-score, and the receiver operating characteristic (ROC) curve are used to assess model accuracy and effectiveness in identifying churned customers.

## Model Interpretability
To gain insights into the models' decision-making processes, SHAP (SHapley Additive exPlanations) values are used for interpretability. SHAP values help understand feature importances and the impact of each feature on predicting churn.

![1](https://github.com/khames-lab/E-Commerce-Customer-Churn-Prediction/assets/77197337/31af8079-3a64-4e10-ab89-49308132f9e4)

## Usage
You can use this project to:
- Predict customer churn for your e-commerce platform.
- Identify and understand the factors that contribute to churn.
- Customize and improve the churn prediction models based on your data and needs.

Feel free to adapt and extend the code and analysis for your specific e-commerce business.


