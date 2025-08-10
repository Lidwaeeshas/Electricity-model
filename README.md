# Electricity-model
Electricity Cost Prediction  This project builds a Linear Regression model to predict electricity costs based on several building and environmental features. It demonstrates practical data cleaning, feature engineering, outlier removal, model training, evaluation, and diagnostic checks to ensure model reliability.

# Project Overview

The goal is to accurately estimate electricity costs using features like:

Site area

Structure type

Water consumption

Recycling rate

Utilisation rate

Air quality index

Issue resolution time

Resident count


The project handles data preprocessing steps such as removing duplicates and outliers to improve model performance. It also checks for common linear regression assumptions including multicollinearity, linearity, independence of errors, and normality of residuals.

# Features & Techniques

Data cleaning: duplicate removal, outlier detection with IQR

Categorical variable encoding: One-hot encoding for structure type

Train-test split for model validation

Linear regression model fitting and prediction

Statistical diagnostics:

Variance Inflation Factor (VIF) for multicollinearity

Durbin-Watson test for independence of residuals

Residual plots for linearity and homoscedasticity

Histogram for normality of errors


Model evaluation metrics: R², Adjusted R², MSE, RMSE, MAE, F-statistic

Statistical significance testing for feature coefficients


# Usage

1. Install required packages:

pip install pandas scikit-learn statsmodels matplotlib numpy


2. Prepare the dataset file named electricity_cost_dataset.csv.


3. Run the script to train the model, perform diagnostics, and evaluate results.


4. Modify the code to customize the model or experiment with other features.



# Results Summary

Model explains approximately {adjusted R² value here}% of the variance in electricity costs.

Prediction error (RMSE) is about {rmse} units.

Feature significance and multicollinearity are evaluated to ensure reliable predictors.

# What I Learned

Importance of preprocessing and outlier removal in regression models

How to encode categorical variables for ML models

Checking key assumptions of linear regression models for valid inference

How to interpret evaluation metrics and statistical tests for model quality
