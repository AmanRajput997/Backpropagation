# Backpropagation Explored: Manual vs. Keras for Classification and Regression

This repository contains a collection of Jupyter notebooks that demonstrate the implementation of the backpropagation algorithm for both classification and regression tasks. The notebooks provide a clear comparison between building neural networks from scratch and using a high-level library like Keras.

Project Overview : 


The core of this project is to showcase the fundamental mechanics of backpropagation. By walking through both manual and Keras-based implementations, you'll gain a deeper understanding of how neural networks learn.

Key Concepts Illustrated:


• Forward Propagation: The process of input data moving through the network to generate an output.

• Loss Calculation: Quantifying the difference between the model's prediction and the actual target value.

• Backward Propagation: The process of calculating the gradient of the loss function with respect to the network's weights and biases.

• Parameter Updates: Adjusting the weights and biases to minimize the loss.

Notebooks : 


This repository includes the following notebooks:

1. Backpropagation for Classification (Manual)
• File: [Backpropagation_Classification_Manually.ipynb](https://github.com/AmanRajput997/Backpropagation/blob/main/Backpropagation_Classification_Manually.ipynb)

• Description: This notebook implements a simple neural network from scratch to solve a binary classification problem. It details the step-by-step process of forward propagation, loss calculation (binary cross-entropy), and backpropagation to update the model's weights and biases.

2. Backpropagation for Classification (Keras)
• File: [Backpropagation_Classification_by_keras.ipynb](https://github.com/AmanRajput997/Backpropagation/blob/main/Backpropagation_Classification_by_keras.ipynb)

• Description: This notebook demonstrates how to build and train the same classification model using the Keras library. It highlights the simplicity and efficiency of using a high-level API for building neural networks.

3. Backpropagation for Regression (Manual)
• File: [Backpropagation_Regression_Manually.ipynb](https://github.com/AmanRajput997/Backpropagation/blob/main/Backpropagation_Regression_Manually.ipynb)

• Description: This notebook provides a from-scratch implementation of a neural network for a regression task. It covers the nuances of adapting the backpropagation algorithm for continuous target variables, using mean squared error as the loss function.

4. Backpropagation for Regression (Keras)
• File: [Backpropagation_Regression_by__Keras.ipynb](https://github.com/AmanRajput997/Backpropagation/blob/main/Backpropagation_Regression_by__Keras.ipynb)

• Description: This notebook showcases the Keras implementation of the regression model, allowing for a direct comparison with the manual approach and demonstrating the power of Keras for rapid prototyping.

5. Memoization Demo
• File:[Memoization_Demo](https://github.com/AmanRajput997/Backpropagation/blob/main/Memoization_Demo.ipynb)

• Description: This notebook explains the concept of memoization, a key optimization technique that makes backpropagation computationally efficient. It illustrates how storing and reusing intermediate calculations (a form of memoization) is fundamental to the backpropagation algorithm.
   

How to Use


To run these notebooks, you'll need to have Python and the following libraries installed:

• Jupyter Notebook

• NumPy

• Pandas

• TensorFlow

• Keras

You can install the necessary libraries using pip:

pip install numpy pandas tensorflow keras jupyter

Once the libraries are installed, you can launch Jupyter Notebook and open the .ipynb files.
