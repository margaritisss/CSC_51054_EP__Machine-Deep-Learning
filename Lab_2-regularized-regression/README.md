# Lab 2: Regularized Regression (Ridge & Lasso)

This repository contains the Jupyter Notebook for Lab 2 of the INF 554 course. This lab introduces and implements regularized regression techniques, specifically Ridge and Lasso regression, to prevent overfitting and improve model generalization.

## Lab Overview

The primary goal of this lab is to understand and apply regularization to linear models. While standard Ordinary Least Squares (OLS) can be prone to overfitting, especially with a high number of features or complex polynomial transformations, regularization adds a penalty term to the loss function to constrain the model's coefficients.

This lab explores two key regularization methods:
* **Ridge Regression (L2 Regularization):** Adds a penalty equivalent to the square of the magnitude of coefficients. This method shrinks coefficients but does not set them to zero.
* **Lasso Regression (L1 Regularization):** Adds a penalty equivalent to the absolute value of the magnitude of coefficients. This can shrink some coefficients to exactly zero, effectively performing feature selection.

## Key Concepts

* **Regularization:** A technique used to prevent overfitting by adding a penalty for model complexity.
* **Ridge Regression (L2):** Implemented to handle multicollinearity and shrink model coefficients.
* **Lasso Regression (L1):** Implemented for its ability to perform feature selection by forcing some coefficients to zero.
* **Mean Squared Error (MSE):** The metric used to evaluate model performance.
* **Hyperparameter Tuning:** The process of finding the optimal regularization parameter ($\lambda$) by evaluating the model's performance on a validation set.
* **Coefficient Analysis:** Observing how Ridge and Lasso affect the model's coefficients as the regularization strength changes.

## Tasks Performed in the Notebook

The `Lab_2.ipynb` notebook guides you through the following tasks:

1.  **Data Loading and Preprocessing:** Loading the provided dataset and preparing it for modeling.
2.  **Implementation of Ridge Regression:**
    * Deriving and implementing the closed-form solution for Ridge Regression.
    * Evaluating the model's MSE on training and validation sets for different values of the regularization parameter $\lambda$.
    * Plotting the MSE to find the optimal $\lambda$.
3.  **Implementation of Lasso Regression:**
    * Implementing Lasso Regression using a coordinate descent algorithm.
    * Evaluating and plotting the MSE against different $\lambda$ values to find the optimal hyperparameter.
4.  **Coefficient Analysis:** Plotting the values of the model coefficients ($\beta$) against the regularization parameter $\lambda$ for both Ridge and Lasso to visualize how each method impacts feature importance.

## How to Use

To run this lab, you will need a Python environment with the following libraries installed:
* `numpy`
* `matplotlib`

Simply open and execute the cells in the `Lab_2.ipynb` notebook using a Jupyter environment like Jupyter Notebook, JupyterLab, or Google Colab.
