# Project 02 – Multiple Linear Regression with One-Hot Encoding

## Overview
This project is part of my Machine Learning learning journey. It focuses on predicting house prices using Multiple Linear Regression and handling categorical variables through One-Hot Encoding.

## Project Objective
Build a Machine Learning model to predict house prices in lakhs using multiple input features, including property location, property type, furnishing, and other available numerical features.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- OneHotEncoder
- Linear Regression

## Machine Learning Concepts Covered
- Data loading and exploration
- Understanding dataset information using `df.info()`
- Descriptive statistics using `df.describe()`
- Categorical data preprocessing
- One-Hot Encoding
- Independent and dependent variables
- Train-test splitting
- Multiple Linear Regression
- Model training using `model.fit()`
- Predictions using `model.predict()`

## One-Hot Encoding
Used Scikit-learn's `OneHotEncoder` to convert categorical columns into numerical features.

Categorical columns handled:
- Location
- Property_Type
- Furnishing

## Model Development
1. Imported the required libraries.
2. Loaded and explored the housing dataset.
3. Applied One-Hot Encoding to categorical columns.
4. Combined encoded columns with the original dataset.
5. Removed the original categorical columns.
6. Separated independent variables (X) and target variable (y).
7. Split the dataset into training and testing sets (80:20).
8. Created and trained a Linear Regression model.
9. Generated house price predictions.

## Target Variable
`House_Price_Lakhs`

## Key Learning Outcomes
- Understanding Multiple Linear Regression.
- Learning how to handle categorical variables.
- Understanding One-Hot Encoding.
- Preparing datasets for Machine Learning.
- Training a regression model with multiple features.
- Generating predictions using Scikit-learn.

## Future Improvements
- Evaluate model performance using MAE, MSE, RMSE and R².
- Visualize actual versus predicted house prices.
- Experiment with different feature combinations.
- Compare model performance with other regression algorithms.

## Status
Initial model training and prediction completed. Model evaluation and further improvements are planned.

---

**Author:** Kishore Kumar

*Part of my hands-on Machine Learning learning journey.*
