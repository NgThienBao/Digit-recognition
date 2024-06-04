# Multilayer Perceptron (MLP) Model for MNIST Dataset

In this repository, we create and train a Multilayer Perceptron (MLP) model on the MNIST dataset using Keras.

## Introduction

Multilayer Perceptrons (MLPs) usually mean fully connected networks, where each neuron in one layer is connected to all neurons in the next layer. These networks are also known as deep feedforward or feedforward neural networks. MLPs are commonly used in simple logistic and linear regression problems.

## Objective

The objective is to create a neural network for identifying numbers based on handwritten digits. For example, when the input to the network is an image of a handwritten number 8, the prediction should also be the digit 8.

## Dataset

The MNIST dataset, which is a collection of 70,000 handwritten digits, is used for training and validating the neural network. This dataset is often considered the "Hello World!" of deep learning.

## Requirements

- Python 3.x
- numpy
- pandas
- keras
- matplotlib

## How to Run the Code

1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Ensure you have the necessary libraries installed. You can install them using pip:
    ```sh
    pip install numpy pandas keras matplotlib
    ```
3. **Run the Script**: Execute the Python script to train and evaluate the model:
    ```sh
    python mnist_mlp.py
    ```

## Code Explanation
In file.doc or Word.ipynb
### Import Libraries

```python
import numpy as np
import pandas as pd
import os
import keras
from keras.datasets import mnist
from keras.models import Model
from keras.layers import Dense, Input, Conv2D, MaxPooling2D, Dropout, Flatten
from keras import backend as k
from matplotlib import pyplot as plt