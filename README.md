# House Price Prediction

This project aims to predict house prices using various machine learning algorithms. It involves data preprocessing, feature engineering, model building, and evaluation.

## Overview

The project performs the following steps:

1. **Data Loading and Preprocessing**:
   - Imports necessary libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.
   - Loads the training and testing data from CSV files.
   - Concatenates the data for preprocessing.
   - Checks for missing values and imputes them using appropriate strategies.

2. **Feature Engineering**:
   - One-hot encodes categorical variables to prepare them for modeling.
   
3. **Model Building and Evaluation**:
   - Standardizes the features using StandardScaler.
   - Builds different regression models including Linear Regression, Ridge Regression, Lasso Regression, and Random Forest.
   - Evaluates the models using cross-validation and calculates Root Mean Squared Error (RMSE).
   - Chooses the best model based on the lowest cross-validated RMSE.

4. **Prediction and Submission**:
   - Trains the best model on the entire training data.
   - Makes predictions on the test data.
   - Saves the predictions to a CSV file for submission.
