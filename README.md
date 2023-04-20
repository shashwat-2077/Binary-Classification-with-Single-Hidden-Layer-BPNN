# Binary-Classification-with-Single-Hidden-Layer-BPNN
This repository contains code for a binary classification problem using a single hidden layer Backpropagation Neural Network (BPNN) model.

The dataset used is Weather(Rainfall) Prediction Data, which has features such as Humidity, Temperature, Precipitation and Pressure. The objective is to predict whether it will rain or not in the given condition.

The "Binary Classification with single hidden layer BPNN" script contains functions to load and preprocess the data. The preprocessing steps include feature scaling and splitting the data into training and test sets. It defines the architecture of the BPNN model with a single hidden layer. The model is implemented using the SkLearn library. The hyperparameters of the model such as the learning rate, number of epochs, and number of neurons in the hidden layer can be modified in this script. It then trains the BPNN model using the training data and saves the trained model weights. It then loads the trained model weights and evaluates the model's performance on the test data. The evaluation metrics used are accuracy, precision, recall, and F1-score.Then we can predict the rainfall based on our provided values

To run the code, clone the repository and run Binary Classification with single hidden layer BPNN.ipynb. The notebook provides step-by-step instructions on how to load the data, preprocess it, train the model, and evaluate its performance.

Dependencies: NumPy, Pandas, Scikit-learn

Contributors: Paritosh Mathur, Himanshu Bungla, Shashwat Pattanayak
