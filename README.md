# Regression Models – Machine Learning

## Overview
This repository contains implementations of fundamental regression techniques used in machine learning. The notebooks demonstrate how to build, evaluate, and interpret different regression models.

The following models are covered:
- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression


## Repository Structure
├── SimpleLinear_regression.ipynb <br>
├── MultipleLinear_Regression.ipynb <br>
├── Polynomial_regression.ipynb <br>
└── README.md


## 1. Simple Linear Regression
- Models relationship between one independent variable and dependent variable
- Fits a straight line:

  y = mx + c

### Key Steps:
- Data preprocessing
- Model training using Linear Regression
- Visualization of regression line
- Model evaluation


## 2. Multiple Linear Regression
- Uses multiple independent variables
- General form:

  y = b0 + b1x1 + b2x2 + ... + bnxn

### Key Concepts:
- Feature selection
- Multicollinearity handling
- Model fitting using OLS
- Interpretation of coefficients


## 3. Polynomial Regression
- Captures non-linear relationships
- Transforms features into polynomial terms:

  y = b0 + b1x + b2x^2 + ... + bnx^n

### Key Steps:
- Polynomial feature transformation
- Model fitting using linear regression
- Visualization of curved fit


## Model Evaluation Metrics

### Mean Squared Error (MSE)
- Measures average squared difference between actual and predicted values
- Sensitive to outliers

### Mean Absolute Error (MAE)
- Average absolute difference
- More robust to outliers

### Root Mean Squared Error (RMSE)
- Square root of MSE
- Same unit as target variable

### R-squared (R²)
- Measures goodness of fit
- Range: 0 to 1

### Adjusted R-squared
- Adjusts R² for number of features
- Prevents overfitting


## Key Insights
- Linear regression assumes linearity, independence, homoscedasticity, and normality
- Polynomial regression helps capture non-linear patterns
- Evaluation metrics help in model comparison and selection
- Trade-off between bias and variance is important


## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Future Improvements
- Add Regularization (Ridge, Lasso)
- Add Cross-validation
- Deploy model using FastAPI
- Include real-world datasets
