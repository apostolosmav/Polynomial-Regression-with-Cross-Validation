# Polynomial Regression with K-Fold Cross-Validation

This project demonstrates polynomial regression on a dataset using K-Fold cross-validation. 
It evaluates polynomial models of different degrees, computes their mean squared error (MSE), 
and visualizes the results to select the best-fitting polynomial.

## Project Overview

The notebook follows these steps:

1. **Import Libraries** – pandas, numpy, scikit-learn, matplotlib.
2. **Load Data** – Read dataset from a CSV file.
3. **Prepare Features and Target** – Separate input features (X) and target variable (y).
4. **Define K-Fold Cross-Validation Function** – Evaluate polynomial models of degrees 1 to 4.
5. **Perform K-Fold Cross-Validation** – Calculate mean squared error for each degree.
6. **Visualize Results** – Plot original data and regression curves; highlight the best fit.
7. **Interpretation** – Analyze plots and MSE values to choose the optimal polynomial degree.

## Installation

Make sure you have Python 3 installed.
