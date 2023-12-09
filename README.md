# Titanic-Classification
Machine Learning From Disaster




**Best Preforming model** : SVM with kernel set to linear, accuracy score: 100 and mean squared error: 0.

## Overview

This repository contains code for a Titanic classification project. The goal is to predict the survival status of passengers on the Titanic using machine learning techniques. The dataset used is derived from the famous Titanic dataset, encompassing information about passengers, such as age, gender, class, and more.

## Dataset

The dataset comprises various features, including:

- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Binary variable indicating survival (1) or not (0).
- **Pclass**: Ticket class (1st, 2nd, or 3rd).
- **Name**: Passenger's name.
- **Sex**: Passenger's gender.
- **Age**: Passenger's age.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid for the ticket.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Getting Started
# Data Cleaning
Data cleaning stats with finding Nan values in dataset. These values can either be remove or replaced with adequate data. Then data such as PassingerID, Ticket and Name are all unique values which does not contribute to training hence can be removed. 

# Data Pre-Processing
This involves Labled encoding where all object data types are converted into integers. This if followed uo by data visualizations and analysis which provides us insights od data which are not usually observed when looking at raw data.

# Model Training

For the model training phase, we employ various machine learning algorithms to predict the survival outcomes of passengers. The dataset is split into training and testing sets, and the following models are utilized:

1. **Logistic Regression**: A baseline model to establish a benchmark for performance.
2. **Random Forest Classifier**: A more complex model that can capture non-linear relationships.
3. **Support Vector Machine (SVM)**: A model suitable for both linear and non-linear data.

Hyperparameter tuning is performed to optimize each model's performance. Evaluation metrics such as accuracy, precision, recall, and F1 score are utilized to assess the model's effectiveness.

# Model Evaluation 

Models are compared with each other on the basis of accuracy score and mean squared error. Confusion Matrices are obtained for further visualization of performance of each model.

