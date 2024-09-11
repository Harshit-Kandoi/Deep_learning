# Handwritten Digit Classification using Neural Networks

This project demonstrates the implementation of a neural network model to classify handwritten digits using the popular **MNIST** dataset. The model is trained on a set of grayscale images of handwritten digits (0-9) and is capable of predicting the digit from a given image with high accuracy.

# Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

# Introduction

The "MNIST" dataset contains 70,000 images of handwritten digits, split into a training set of 60,000 images and a test set of 10,000 images. Each image is a 28x28 grayscale image, representing a digit from 0 to 9.

The goal of this project is to develop a neural network model that can classify handwritten digits with high accuracy. The network is implemented using libraries like TensorFlow and Keras, and the model is trained on the training dataset while testing is done on the unseen test dataset.

# Technologies Used

- **Python 3.7+**
- **TensorFlow 2.x** for building and training the neural network
- **Keras** for high-level model abstraction
- **NumPy** for data manipulation
- **Matplotlib** for visualization
- **Jupyter Notebooks** for interactive exploration

# Dataset

The project uses the "MNIST" dataset, which is preloaded into Keras through `tensorflow.keras.datasets`. You can also download it from the official [MNIST page](http://yann.lecun.com/exdb/mnist/).

# Installation

1. Clone the repository.
2. Set up a virtual environment.
3. Install the required dependencies.
4. Run the Jupyter notebook for exploring the dataset.
   
# Usage

1. Train the model.
2. Evaluate the model.
3. Make Predictions.

# Model Architecture

The neural network used in this project has the following architecture:

- Input Layer: 784 nodes (28x28 pixels)
- Hidden Layer 1: Dense layer with 128 neurons and ReLU activation
- Hidden Layer 2: Dense layer with 64 neurons and ReLU activation
- Output Layer: 10 neurons (for digits 0-9) with Softmax activation

# Results

The neural network achieves an accuracy of over 98% on the test dataset. Detailed results, including a confusion matrix and loss/accuracy plots, are provided in the Jupyter notebook.

# Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are welcome.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# License

This project is licensed under the MIT License. See the `LICENSE` file for details.
