# House Price Prediction Notebook
## Introduction
This Jupyter notebook focuses on predicting house prices using a dataset with features such as longitude, latitude, housing median age, total rooms, total bedrooms, population, households, median income, and ocean proximity. The goal is to build a robust regression model for predicting house prices.

# Contents
## Data Preprocessing
Handling Null Values: Null values in the dataset were removed to ensure a clean and complete dataset.
Univariate Visualization: Exploratory data analysis (EDA) using various visualizations to understand the distribution of individual features.
## Bivariate Visualization

Exploring relationships between pairs of variables to identify potential patterns and correlations.
## Multivariate Visualization

Analyzing interactions among multiple variables to gain insights into complex relationships within the dataset.
## Correlation Analysis

Calculating correlations between features and the target variable (median house value) to identify influential predictors.
## Feature Engineering

Transforming or creating new features to enhance the predictive power of the model.
## Dataset Splitting

Dividing the dataset into training and testing sets for model evaluation.
## Handling Nulls

Employing pipelining for imputing and standardization to streamline the preprocessing steps.
## Model Building and Evaluation

Utilizing three regression models:

 Linear Regression: RMSE for training set --> 67871.07, R2 Score --> 0.65 
 
 SGD Regression: RMSE for training set --> 68016.30, R2 Score --> 0.65
 
 KNN Regression: RMSE for training set --> 61206.09, R2 Score --> 0.72
 

## How to Use
- Clone the repository to your local machine.
- 
- Ensure you have the required dependencies installed (i have provided already inside reqs.txt file inside the repository) .
- 
- Open and run the Jupyter notebook.
- 
- Follow the step-by-step guide for data preprocessing, visualization, and model building.
- 
- Experiment with hyperparameters and additional feature engineering to improve model performance.
