# The_sparks_foundation_project

## Project Title: Student Score Prediction based on Study Hours

## Problem Statement:

This project aims to predict the percentage of marks that a student is expected to score based on the number of hours they studied. It involves building a simple linear regression model with one input variable, which is the number of hours studied.

## About the Dataset:

The dataset contains two columns:
Hours: The number of hours a student studied.
Scores: The corresponding scores obtained by the student.

## Key Objectives:
The primary objectives of the project are as follows:
Data Exploration: Tried to understand the dataset by exploring its structure and characteristics.
Data Preprocessing: Prepared the data for model training and testing, including data splitting and feature selection.
Model Training: Trained the selected model using the training dataset.
Model Evaluation: Assess the model's performance using various evaluation metrics.
Prediction: Used the trained model to predict a student's score based on the number of hours studied.

## Data Processing:

Data Loading: Loaded the dataset into a Python environment, using Pandas.
Data Exploration: Analyze the dataset to understand its structure and characteristics.
Data Preprocessing: Prepare the data by splitting it into training and testing sets using train_test_split from Scikit-Learn.
Model Selection: Choosed a suitable regression model. In this case, a Linear Regression model is selected.
Model Training: Fit the Linear Regression model to the training data using fit.
Model Evaluation: Evaluate the model's performance using various metrics like Mean Absolute Error, Mean Absolute Percentage Error, Mean Squared Error, and R-squared.
Prediction: Used the trained model to predict a student's score for a given number of study hours.

## Insights:

Based on the analysis and model evaluation, the following insights can be drawn:

The Linear Regression model has been trained and evaluated with a good R-squared score (0.9735), indicating a strong relationship between study hours and scores.

The model predicts that a student studying for 9.25 hours a day is expected to score approximately 93.46%.

