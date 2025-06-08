# Lab 4: Support Vector Machines (SVM) for Classification

This repository contains the Jupyter Notebook for Lab 4 of the INF 554 course. This lab provides a hands-on implementation of a linear **Support Vector Machine (SVM)**, a powerful and widely used supervised learning algorithm for classification tasks.

## Lab Overview

The core idea behind SVMs is to find the optimal hyperplane that best separates data points of different classes in a feature space. The "best" hyperplane is the one that has the largest margin—the maximum distance between the hyperplane and the nearest data point from either class. This principle of margin maximization makes SVMs robust and effective classifiers.

This lab covers the implementation of a linear SVM from scratch, including handling non-linearly separable data using a "soft margin" approach with slack variables. The model is trained using a sub-gradient descent algorithm to minimize the hinge loss function.

## Key Concepts Covered

-   **Support Vector Machines (SVM):** Understanding the theory behind margin maximization.
-   **Hyperplane:** The decision boundary used by the SVM to separate classes.
-   **Hinge Loss:** The loss function used for training "maximum-margin" classifiers like SVMs.
-   **Sub-gradient Descent:** An optimization algorithm used to train the SVM by minimizing the hinge loss.
-   **Soft Margin & Slack Variables:** A modification to the SVM to handle data that is not perfectly linearly separable.
-   **Model Evaluation:** Assessing the classifier's performance using **accuracy**.
-   **Visualization:** Plotting the decision boundary and the margins to understand the SVM's behavior.

## Tasks Performed in the Notebook

The `Lab_4.ipynb` notebook walks through the following key implementation steps:

1.  **Data Loading:** Importing and visualizing the classification dataset.
2.  **Linear SVM Implementation:** Building an SVM model class from scratch.
3.  **Hinge Loss Function:** Implementing the loss function that drives the SVM's learning process.
4.  **Sub-gradient Descent:** Writing the training loop to optimize the model's weights.
5.  **Prediction and Evaluation:** Making predictions on a test set and calculating the model's accuracy.
6.  **Visualization:** Creating a plot that shows the final decision boundary, the margins, and the support vectors identified by the model.

## How to Use

To run the code in this lab, you will need a Python environment with the following libraries installed:
* `numpy`
* `matplotlib`

You can run the script by opening `Lab_4.ipynb` in a Jupyter environment (such as Jupyter Notebook, JupyterLab, or Google Colab) and executing the cells in order.
