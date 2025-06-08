# Lab 3: Logistic Regression for Classification

This repository contains the Jupyter Notebook for Lab 3 of the INF 554 course. This lab focuses on building a binary classifier from scratch using **Logistic Regression** and understanding its underlying mechanics, including the use of the sigmoid function and gradient descent for optimization.

***

## Lab Overview 📝

This project transitions from regression to classification tasks. Logistic Regression is a fundamental algorithm for binary classification that models the probability of a given input belonging to a particular class.

Instead of fitting a straight line to the data as in linear regression, logistic regression uses the **sigmoid function** to map the output of a linear equation to a value between 0 and 1. This value represents the probability of the positive class. The model's parameters are then optimized by minimizing a loss function—in this case, the **negative log-likelihood**—using gradient descent.

***

## Key Concepts 🧠

-   **Binary Classification**: Differentiating between two distinct classes.
-   **Logistic (Sigmoid) Function**: The core function used to map outputs to probabilities.
-   **Decision Boundary**: The threshold used to separate the two classes based on predicted probabilities.
-   **Loss Function**: Understanding and implementing the **Negative Log-Likelihood** for a binary classification problem.
-   **Gradient Descent**: The optimization algorithm used to train the model by iteratively adjusting weights to minimize the loss.
-   **Model Evaluation**: Assessing the classifier's performance using **accuracy** as a metric.

***

## Tasks Performed in the Notebook 💻

The `Lab_3.ipynb` notebook provides a step-by-step guide to:

1.  **Data Loading**: Importing and preparing a dataset with two classes.
2.  **Sigmoid Function**: Implementing the sigmoid activation function.
3.  **Model Implementation**: Building the logistic regression model class.
4.  **Loss Calculation**: Implementing the negative log-likelihood loss function.
5.  **Gradient Descent**: Writing the gradient descent algorithm to train the model.
6.  **Training and Evaluation**: Training the logistic regression classifier and evaluating its accuracy on a test set.
7.  **Visualization**: Plotting the data points and the learned decision boundary to visualize the model's performance.

***

## How to Use 🚀

To run this lab, you'll need a Python environment with the following libraries installed:
* `numpy`
* `matplotlib`

You can run the script by opening `Lab_3.ipynb` in a Jupyter environment (like Jupyter Notebook, JupyterLab, or Google Colab) and executing the cells sequentially.
