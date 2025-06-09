# Lab 9: Gaussian Mixture Models (GMM)

This repository contains the Jupyter Notebook for Lab 9 of the INF 554 course. This lab explores **Gaussian Mixture Models (GMMs)**, a powerful probabilistic model for unsupervised clustering. The model is implemented from scratch using the **Expectation-Maximization (E-M)** algorithm.

## Lab Overview 

Gaussian Mixture Models offer a flexible approach to clustering by assuming that the data points are generated from a mixture of a finite number of Gaussian distributions with unknown parameters. Unlike K-means, which creates circular clusters, GMMs can fit elliptical clusters, making them suitable for a wider variety of data distributions.

The core of this lab is the implementation of the **Expectation-Maximization (E-M)** algorithm, which is an iterative method for finding the maximum likelihood estimates of the parameters of the GMM.

-   **E-step (Expectation):** Calculates the probability (or "responsibility") of each data point belonging to each of the Gaussian components.
-   **M-step (Maximization):** Updates the parameters (mean, covariance, and mixing coefficient) of each Gaussian distribution to maximize the likelihood of the data given the responsibilities.

These two steps are repeated until the model parameters converge.

## Key Concepts Covered

-   **Unsupervised Learning & Clustering:** Grouping data without predefined labels.
-   **Gaussian Mixture Models (GMM):** A probabilistic model that represents data as a mixture of Gaussian distributions.
-   **Expectation-Maximization (E-M):** An iterative algorithm for finding maximum likelihood estimates in statistical models with latent variables.
-   **Probability Density Function (PDF):** Used to model the Gaussian components.
-   **Responsibilities:** The posterior probabilities of a data point belonging to each cluster.
-   **Covariance:** A measure that allows for modeling elliptical-shaped clusters.

## Tasks Performed in the Notebook 

The `Lab_9.ipynb` notebook provides a complete guide to:

1.  **Data Generation:** Creating a synthetic dataset that is well-suited for GMM clustering.
2.  **E-Step Implementation:** Writing a function to calculate the responsibilities of each data point for each cluster.
3.  **M-Step Implementation:** Writing a function to update the model's parameters (means, covariances, and mixing coefficients) based on the current responsibilities.
4.  **Training Loop:** Combining the E and M steps into an iterative algorithm that runs until convergence.
5.  **Visualization:** Plotting the final clusters, represented by ellipses that show the mean and covariance of each learned Gaussian distribution.

## How to Use 

To run the code in this lab, you will need a Python environment with the following libraries installed:

-   `numpy`
-   `matplotlib`
-   `scipy`

Simply open `Lab_9.ipynb` in a Jupyter environment (like Jupyter Notebook, JupyterLab, or Google Colab) and execute the cells in order to see the implementation and results.
