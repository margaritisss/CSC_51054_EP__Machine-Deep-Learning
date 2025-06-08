# Lab 6: Neural Networks from Scratch

This repository contains the Jupyter Notebook for Lab 6 of the INF 554 course. This lab provides a fundamental understanding of **Neural Networks** by guiding you through the process of building and training a simple network from scratch using Python and NumPy.

## Lab Overview 🧠

Neural Networks are a cornerstone of modern machine learning and deep learning. This lab demystifies the "black box" by breaking down the core components of a neural network. You will implement the essential mechanisms that allow a network to learn from data, including the forward pass, activation functions, backpropagation for gradient calculation, and parameter updates via gradient descent.

The project culminates in a `NeuralNetwork` class that encapsulates the entire process, which is then trained on a dataset to perform classification.

## Key Concepts Covered

-   **Neural Network Architecture:** Understanding the structure of layers (input, hidden, output) and neurons.
-   **Forward Propagation:** The process of passing input data through the network to generate an output.
-   **Activation Functions:** Implementing the **ReLU (Rectified Linear Unit)** function to introduce non-linearity.
-   **Loss Function:** Calculating the error of the network's predictions.
-   **Backpropagation:** The core algorithm for computing the gradients of the loss function with respect to the network's weights and biases.
-   **Gradient Descent:** The optimization algorithm used to update the network's parameters and minimize the loss.

## Tasks Performed in the Notebook 💻

The `Lab_6.ipynb` notebook provides a detailed, step-by-step implementation of:

1.  **Network Initialization:** Setting up the layers and initializing the weights and biases of the neural network.
2.  **Forward Pass:** Implementing the logic to process an input and produce a prediction.
3.  **Backward Pass:** Implementing the backpropagation algorithm to calculate the gradients for each parameter.
4.  **Parameter Update:** Using the computed gradients to update the model's weights and biases.
5.  **Training Loop:** Combining all the components into a training function that iteratively improves the model's performance.
6.  **Model Evaluation:** Making predictions on a test set and measuring the accuracy of the trained network.

## How to Use 🚀

To run the code in this lab, you will need a Python environment with the following libraries:

-   `numpy`
-   `matplotlib`

Simply open `Lab_6.ipynb` in a Jupyter environment (like Jupyter Notebook, JupyterLab, or Google Colab) and execute the cells sequentially to follow the implementation and see the results.
