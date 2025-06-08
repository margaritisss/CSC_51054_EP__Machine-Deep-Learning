# Lab 8: K-Means Clustering

This repository contains the Jupyter Notebook for Lab 8 of the INF 554 course. This lab focuses on implementing the **K-means clustering algorithm**, a popular and fundamental method in **unsupervised machine learning**.

## Lab Overview 

K-means clustering is an algorithm used to partition a dataset into a pre-determined number of clusters (K). The main objective is to group similar data points together based on their features. The algorithm works iteratively to assign each data point to the cluster with the nearest mean (or "centroid"), and then recalculates the centroids based on the new assignments. This process continues until the cluster assignments no longer change.

This lab provides a from-scratch implementation of the K-means algorithm, allowing for a deep understanding of its core mechanics.

## Key Concepts Covered

-   **Unsupervised Learning:** Learning from data without labeled outcomes.
-   **Clustering:** The task of grouping a set of objects in such a way that objects in the same group (or "cluster") are more similar to each other than to those in other groups.
-   **K-Means Algorithm:** The iterative process of assigning points to clusters and updating centroids.
-   **Centroids:** The center point (mean) of a cluster.
-   **Euclidean Distance:** The distance metric used to determine the closeness of data points to centroids.
-   **Objective Function:** Minimizing the sum of squared distances between data points and their respective cluster centroids.

## Tasks Performed in the Notebook 

The `Lab_8.ipynb` notebook provides a step-by-step guide to implement and visualize the K-means algorithm:

1.  **Data Generation:** Creating a synthetic dataset suitable for clustering.
2.  **Centroid Initialization:** Randomly initializing the starting positions of the cluster centroids.
3.  **Cluster Assignment:** Assigning each data point to the nearest centroid.
4.  **Centroid Update:** Recalculating the position of each centroid based on the mean of its assigned points.
5.  **Training Loop:** Creating an iterative process that repeats the assignment and update steps until convergence.
6.  **Visualization:** Plotting the data points, their cluster assignments, and the final positions of the centroids to visualize the result of the algorithm.

## How to Use 

To run the code in this lab, you will need a Python environment with the following libraries:

-   `numpy`
-   `matplotlib`

Simply open `Lab_8.ipynb` in a Jupyter environment (like Jupyter Notebook, JupyterLab, or Google Colab) and execute the cells in order to see the K-means algorithm in action.
