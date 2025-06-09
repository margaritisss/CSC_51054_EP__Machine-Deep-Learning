# Graded Assessment: Income Level Prediction (20% of Final Grade)

This repository contains the Jupyter Notebook for a graded assessment in the INF 554 course. This project accounts for **20% of the final exam grade** and involves building a complete machine learning pipeline to predict whether an individual's income exceeds $50,000 per year based on census data.

## Project Overview 

The goal of this assessment is to apply various classification models to a real-world problem, involving a full pipeline from data cleaning to model evaluation.

Three different classification models are implemented and compared:
1.  **Logistic Regression**
2.  **Linear Support Vector Machine (SVM)**
3.  **Random Forest Classifier**

The final performance of each model is evaluated on a held-out test set to provide an unbiased measure of their predictive accuracy.

## Dataset

The project uses the **"Adult" dataset** from the UCI Machine Learning Repository, which contains 14 features from 1994 census data.

-   **Target Variable**: `income` (binary: `<=50K` or `>50K`)
-   **Features**: A mix of continuous and categorical attributes like `age`, `workclass`, `education`, `occupation`, and `hours-per-week`.

## Machine Learning Pipeline 

The `Assessment.ipynb` notebook implements the following steps:

1.  **Data Cleaning**: The dataset is loaded, and missing values (represented by `?`) are handled.
2.  **Preprocessing**: Categorical features are converted into a numerical format using one-hot encoding, and the data is split into training and testing sets.
3.  **Model Training**: The three classifiers are trained on the preprocessed training data.
4.  **Evaluation**: Each model makes predictions on the test set, and their **accuracy** is calculated and compared to determine the best-performing model.

## How to Use 

To run this assessment, you'll need a Python environment with the following libraries:
* `pandas`
* `numpy`
* `sklearn`

Open `Assessment.ipynb` in a Jupyter environment and execute the cells sequentially to see the implementation and results.
