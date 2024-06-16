MNIST Dataset Neural Network with TensorFlow
This repository contains a Jupyter Notebook that demonstrates how to build and train a neural network using TensorFlow and Keras on the MNIST dataset.

Overview
The notebook includes the following steps:
Importing Libraries: Import TensorFlow and Keras.
Loading the Dataset: Load the MNIST dataset using TensorFlow.
Preprocessing the Data: Normalize the dataset.
Building the Model: Create a neural network model with Keras.
Compiling the Model: Compile the model with an optimizer, loss function, and metrics.
Training the Model: Train the model on the training data.
Evaluating the Model: Evaluate the model on the test data. 

Requirements
To run the notebook, you need to have the following installed:
Python 3.x
Jupyter Notebook
TensorFlow

Model Architecture
The neural network model used in this notebook has the following architecture:
Input layer: Flatten layer to convert 28x28 images to a 1D array.
Hidden layer: Dense layer with 128 neurons and ReLU activation.
Dropout layer: Dropout layer with a rate of 0.2 to prevent overfitting.
Output layer: Dense layer with 10 neurons (one for each class) and softmax activation. 

Results
After training the model for 5 epochs, it achieves an accuracy of approximately 97.76% on the test set.
