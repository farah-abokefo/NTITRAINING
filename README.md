# NTITRAINING
## Machine Learning & Deep Learning Projects

This repository contains multiple machine learning projects implemented in Jupyter Notebooks. Each project demonstrates a different ML task — from image classification to tabular prediction.

### 1️⃣ Fashion MNIST Classifier 

A deep learning model to classify grayscale clothing images from the Fashion MNIST dataset.

Features:

~Data preprocessing and normalization

~One-hot encoding of labels

~Fully connected neural network with dropout layers

~Training with Adam optimizer

~Visualization of learning curves

~Detailed classification report


### 2️⃣ Iris Flower Classifier 

A neural network implemented from scratch with NumPy, predicting iris species.

Features:

~Manual forward/backward propagation

~Sigmoid & softmax activations

~Cross-entropy loss

~Gradient descent optimization

~Feature standardization + one-hot encoding

### 3️⃣ Tabular Predictions: Titanic & House Prices 

A collection of tabular ML tasks focusing on classification (Titanic survival) and regression (House price prediction).

Features

~Handling categorical features with one-hot encoding

~Dealing with missing values (median/mode imputation recommended)

~Fully connected neural network architectures for classification & regression

~Evaluation with accuracy (Titanic) and loss metrics (House Prices)

### 4️⃣ MNIST Digit Classifier 

A simple neural network trained on the MNIST dataset for handwritten digit recognition.

Features:

~Data loaded directly from Keras

~Flatten → Dense(128, ReLU) → Dense(10, softmax)

~Adam optimizer + sparse categorical crossentropy loss

~Training for 25 epochs (batch size 32)