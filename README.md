# PRODIGY_ML_01: Linear Regression Model for House Price Prediction

## Task Overview
This repository contains the implementation of a **linear regression model** to predict house prices based on **square footage**, **number of bedrooms**, and **number of bathrooms**. The task was performed as part of the **Machine Learning Internship Program** at **Prodigy InfoTech**.

## Dataset
The dataset used for this task is the **House Prices - Advanced Regression Techniques** dataset from Kaggle. The dataset can be found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

### Dataset Features:
- **Square Footage**: The size of the house in square feet.
- **Number of Bedrooms**: The number of bedrooms in the house.
- **Number of Bathrooms**: The number of bathrooms in the house.
- **Sale Price**: The target variable, representing the price of the house.

## Task Description
The task involved implementing a **linear regression model** to predict house prices based on the input features:
- Square Footage
- Number of Bedrooms
- Number of Bathrooms

### Steps Performed:
1. **Data Preprocessing**:
   - Loaded and cleaned the dataset.
   - Split the data into training and testing sets.

2. **Model Implementation**:
   - Trained a **Linear Regression model** using scikit-learn on the training data.
   - Predicted house prices for the test data.

3. **Improvement**:
   - Applied a **log transformation** to the target variable (`SalePrice`) to improve the model.
   - Used **StandardScaler** to scale the features for better performance.

4. **Evaluation**:
   - Evaluated the model using **Mean Squared Error (MSE)** and **R-squared**.
   - Compared the predictions with the actual values to assess model performance.

## Model Performance:
- **Mean Squared Error (MSE)**: 2,783,650,138.99
- **R-squared**: 0.6371

The model showed an improvement in accuracy after applying log transformation and feature scaling, with a slight reduction in MSE and a marginal increase in R-squared.
