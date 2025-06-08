# Lab 5: Decision Trees and Random Forests

This repository contains the Jupyter Notebook for Lab 5 of the INF 554 course. This lab covers the implementation of tree-based classification models, starting with a single **Decision Tree** and extending to a more powerful **Random Forest** ensemble.

## Lab Overview

Decision Trees are versatile and intuitive models that make predictions by learning a hierarchy of simple decision rules from the features of the data. They are the fundamental building blocks for more advanced ensemble methods.

This lab first guides you through building a Decision Tree classifier from scratch. It then introduces the Random Forest algorithm, which improves upon single decision trees by creating an ensemble (or "forest") of multiple trees. Each tree in the forest is trained on a random subset of the data and features, which helps to reduce overfitting and improve predictive accuracy.

## Key Concepts Covered

-   **Decision Tree:** A tree-like model of decisions and their possible consequences.
-   **Gini Impurity:** A metric used to measure the quality of a split in the data.
-   **Recursive Splitting:** The process of building a tree by repeatedly finding the best feature and threshold to split the data.
-   **Ensemble Methods:** Techniques that combine multiple learning algorithms to obtain better predictive performance.
-   **Random Forest:** An ensemble method that operates by constructing a multitude of decision trees at training time.
-   **Bootstrap Aggregating (Bagging):** The practice of training each tree on a random sample of the original dataset with replacement.

## Tasks Performed in the Notebook

The `Lab5.ipynb` notebook provides a complete walkthrough of the following steps:

1.  **Node and Tree Implementation:** Creating the basic building blocks for the Decision Tree, including a `Node` class.
2.  **Impurity Calculation:** Implementing the Gini impurity function to evaluate potential splits.
3.  **Finding the Best Split:** Writing a function to iterate through features and find the split that results in the greatest information gain.
4.  **Building the Decision Tree:** Recursively growing the tree until a stopping criterion is met.
5.  **Training and Evaluating the Decision Tree:** Fitting the single tree classifier to the training data and measuring its performance.
6.  **Random Forest Implementation:** Building a `RandomForest` class that creates and manages an ensemble of decision trees.
7.  **Training and Evaluating the Random Forest:** Comparing the performance of the Random Forest against the single Decision Tree to observe the benefits of the ensemble approach.

## How to Use

To run this lab, you will need a Python environment with the following libraries:

-   `numpy`
-   `matplotlib`

Simply open `Lab5.ipynb` in a Jupyter environment (like Jupyter Notebook, JupyterLab, or Google Colab) and execute the cells in order to see the implementation and results.
