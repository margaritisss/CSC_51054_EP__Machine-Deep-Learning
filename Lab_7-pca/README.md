# Lab 7: Principal Component Analysis (PCA)

This repository contains the Jupyter Notebook for Lab 7 of the INF 554 course. This lab focuses on understanding and implementing **Principal Component Analysis (PCA)**, a fundamental and widely-used unsupervised learning technique for dimensionality reduction.

## Lab Overview 

Principal Component Analysis is a powerful method used to reduce the number of variables in a dataset while preserving as much of the original information as possible. It achieves this by transforming the data into a new set of orthogonal (uncorrelated) variables called **principal components**. The first principal component accounts for the largest possible variance in the data, the second component accounts for the second largest, and so on.

This lab provides a from-scratch implementation of PCA, covering the necessary linear algebra concepts like covariance matrices, eigenvectors, and eigenvalues. The algorithm is applied to the digits dataset to visualize high-dimensional data in a lower-dimensional space.

## Key Concepts Covered

-   **Dimensionality Reduction:** The process of reducing the number of random variables under consideration.
-   **Principal Component Analysis (PCA):** A statistical procedure that uses an orthogonal transformation to convert a set of observations of possibly correlated variables into a set of values of linearly uncorrelated variables.
-   **Covariance Matrix:** A matrix that summarizes the relationships between pairs of variables.
-   **Eigenvectors and Eigenvalues:** The mathematical basis for determining the principal components. Eigenvectors represent the directions of the new feature space, and eigenvalues represent the magnitude of the variance in those directions.
-   **Explained Variance:** A measure of how much information (variance) from the original dataset is captured by each principal component.
-   **Data Projection:** Transforming the original data into the new feature space defined by the principal components.

## Tasks Performed in the Notebook 

The `Lab7_solution.ipynb` notebook provides a complete implementation of:

1.  **Data Loading and Standardization:** Loading the digits dataset and standardizing the features.
2.  **Covariance Matrix Calculation:** Computing the covariance matrix of the standardized data.
3.  **Eigen-decomposition:** Calculating the eigenvectors and eigenvalues from the covariance matrix.
4.  **Principal Component Selection:** Sorting the eigenvectors based on their corresponding eigenvalues to identify the principal components.
5.  **Data Transformation:** Projecting the original high-dimensional data onto the new lower-dimensional feature space (e.g., the first two principal components).
6.  **Visualization:** Plotting the transformed data to visualize the separation of different digit classes in 2D.
7.  **Explained Variance Analysis:** Plotting the cumulative explained variance to determine the number of components required to retain a desired percentage of information.

## How to Use 

To run the code in this lab, you will need a Python environment with the following libraries installed:

-   `numpy`
-   `matplotlib`
-   `sklearn` (used for loading the dataset)

You can run the script by opening `Lab7_solution.ipynb` in a Jupyter environment (like Jupyter Notebook, JupyterLab, or Google Colab) and executing the cells in order.
