# Lab 1: Introduction to the Machine Learning Pipeline

This repository contains the code and data for Lab 1 of the INF 554 course. The lab demonstrates the fundamental steps of a machine learning pipeline, from data exploration and preprocessing to model building, evaluation, and selection.

## The Task and Data

The goal of this lab is to build a regression model to predict the weekly growth of Scots pine trees based on environmental measurements.

### Data Description

The dataset, located in the `data` folder, consists of weekly measurements of:

-   **Week number** ($X_1$): The week of the year.
-   **Average measured temperature** ($X_2$): The average temperature for the week.
-   **Soil moisture** ($X_3$): The average soil moisture for the week.
-   **Number of new cells** ($Y$): The target variable, representing the average number of new tracheids (tree cells) measured during the week.

## Implementation of the Machine Learning Pipeline

The machine learning pipeline is implemented in the `Lab_1.ipynb` Jupyter Notebook and covers the following steps:

### 1. Inspecting the Data (Task 1)

The first step involves loading the training data and visualizing the distribution of each variable using histograms. The relationship between the week number and the number of new cells is also plotted to observe the growth season.

### 2. Preprocessing (Task 2)

The data is preprocessed by standardizing each attribute to have a mean of 0 and a standard deviation of 1. This ensures that all variables are considered equally by the model.

### 3. Building a Model (Task 3)

An Ordinary Least Squares (OLS) regression model is implemented to predict the number of new cells. To capture non-linear dependencies, polynomial basis functions are used to create a new feature space.

### 4. Evaluation and Model Selection (Tasks 4-10)

The model is evaluated using the Mean Squared Error (MSE) metric. A validation set is used to compare the model's performance with a baseline model and to assess the impact of outliers. The degree of the polynomial feature transformation is varied to find the optimal model complexity and avoid overfitting.

## How to Run the Code

To run the code, you will need a Python environment with the following libraries installed:

-   `numpy`
-   `matplotlib`

You can then open and run the `Lab_1.ipynb` notebook in a Jupyter environment. The notebook contains all the code and detailed instructions for each task.

## Key Concepts Covered

-   Data exploration and visualization
-   Data preprocessing (standardization)
-   Model building (Ordinary Least Squares)
-   Model evaluation (Mean Squared Error)
-   Model selection and hyperparameter tuning
-   Overfitting and the importance of validation and test sets

This lab provides a hands-on introduction to the essential concepts and practices in the machine learning pipeline.
