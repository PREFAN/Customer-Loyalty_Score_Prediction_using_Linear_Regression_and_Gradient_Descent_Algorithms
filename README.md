#Loyalty_Score_Prediction_using_Linear_Regression_and_Gradient_Descent_Algorithms
This project focuses on predicting customer loyalty scores using Linear Regression and implementing multiple Gradient Descent optimization algorithms from scratch, including:

Batch Gradient Descent (BGD)
Stochastic Gradient Descent (SGD)
Mini-Batch Gradient Descent (MBGD)

The project combines exploratory data analysis (EDA), feature engineering, dimensionality reduction with PCA, regression modeling, and custom optimization techniques to analyze customer purchasing behavior and predict loyalty scores.

Project Overview

Using the dataset Customer Purchasing Behaviors.csv, this project investigates how customer attributes such as:

Age
Annual Income
Purchase Amount
Purchase Frequency

influence the target variable:

Loyalty Score

Because the selected predictors are strongly correlated, the project applies:

Standardization
Principal Component Analysis (PCA)

before fitting a Linear Regression model.

In addition to using built-in machine learning tools, the project also demonstrates how linear regression can be optimized manually through custom implementations of gradient descent algorithms.

Key Features
1. Data Exploration & Preprocessing
Load and inspect the customer purchasing dataset
Check for:
Missing values
Data types
Statistical summaries
Identify:
Categorical attributes
Numerical attributes
2. Exploratory Data Analysis (EDA)
Histograms for feature distribution
Scatterplots for pairwise relationships among numerical variables
Correlation heatmap for identifying strongly related predictors
Boxplots for detecting outliers
3. Feature Selection & Dimensionality Reduction
Select highly correlated predictors:
age
annual_income
purchase_amount
purchase_frequency
Standardize predictors using StandardScaler
Apply PCA to reduce correlated predictors into 1 principal component
4. Linear Regression Modeling
Split data into training and testing sets
Train a Linear Regression model using Scikit-learn
Fit an OLS regression model using Statsmodels
Interpret:
Coefficients
Intercept
R-squared
P-values
F-statistic
5. Model Evaluation

Evaluate regression performance using:

RMSE (Root Mean Squared Error)
R-squared
MSE (Mean Squared Error)
MAPE (Mean Absolute Percentage Error)
MAE (Mean Absolute Error)
6. Gradient Descent from Scratch

This project manually implements and visualizes three optimization methods:

Batch Gradient Descent (BGD)
Updates parameters using the full dataset per iteration
Tracks training loss across epochs
Stochastic Gradient Descent (SGD)
Updates parameters using one sample at a time
Includes data shuffling for each epoch
Mini-Batch Gradient Descent (MBGD)
Updates parameters using small batches of samples
Balances efficiency and stability
7. Loss Curve Visualization
Plots training loss over epochs for:
Batch Gradient Descent
Stochastic Gradient Descent
Mini-Batch Gradient Descent
Technologies Used
Python
Pandas – data loading and preprocessing
NumPy – numerical operations
Matplotlib – plotting and visualization
Seaborn – statistical visualizations
Scikit-learn
LinearRegression
train_test_split
StandardScaler
PCA
Statsmodels
OLS regression analysis
Dataset
File: Customer Purchasing Behaviors.csv
Includes customer-related variables such as:
User ID
Age
Annual Income
Purchase Amount
Purchase Frequency
Loyalty Score (target variable)
Machine Learning Workflow
Load and inspect the dataset
Perform EDA and visualize feature relationships
Detect highly correlated predictors
Standardize selected numerical features
Apply PCA to reduce multicollinearity
Split data into training and testing sets
Train and evaluate a Linear Regression model
Fit and interpret an OLS regression model
Predict loyalty scores on test data
Implement Batch, Stochastic, and Mini-Batch Gradient Descent from scratch
Plot loss curves to compare optimization behavior
Learning Objectives

This project is excellent for understanding:

Regression analysis in machine learning
How multicollinearity can affect models
Why PCA can improve regression performance
How gradient descent works mathematically
The difference between:
Batch Gradient Descent,
Stochastic Gradient Descent,
Mini-Batch Gradient Descent, and 
How to evaluate regression models using multiple error metrics
Use Cases

This project can be useful for:

Customer behavior analysis,
Loyalty score prediction,
Business analytics,
Machine learning education,
Understanding optimization algorithms, and 
Demonstrating regression with dimensionality reduction.
