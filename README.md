# MNIST Digit Classification with Convolutional Neural Network (CNN)

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset using TensorFlow and Keras.

## Overview

The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9). This project builds a CNN to accurately classify these digits.

## Requirements

- Python 3.6+
- TensorFlow 2.x
- NumPy
- Matplotlib

You can install the required packages using:
```bash
pip install tensorflow numpy matplotlib
```

## Project Structure

The project follows these main steps:

1. Data Preprocessing
2. Building the CNN
3. Training the Model
4. Making Predictions

## Usage
The notebook follows the steps:
- Load and preprocess the MNIST dataset
- Build and compile the CNN
- Train the model
- Display a random test image with its predicted and actual label

## Model Architecture

The CNN architecture includes:

- Two convolutional layers with max pooling
- A flatten layer
- A fully connected hidden layer
- An output layer with 10 units (one for each digit)

## Results

The model typically achieves over 98% accuracy on the test set after 25 epochs.

## Customization

You can modify the model architecture, hyperparameters, or training process by editing the relevant sections in the script.

## Author

Anushka Wakankar
