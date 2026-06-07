# Handwritten Digit Recognition Using CNN

## Overview

This project implements a Handwritten Digit Recognition System using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The model is trained on the MNIST dataset to accurately classify handwritten digits from 0 to 9. The project demonstrates the application of Deep Learning and Computer Vision techniques for image classification tasks.

## Features

* Handwritten digit classification (0–9)
* Image preprocessing and normalization
* CNN-based Deep Learning model
* Training and validation on the MNIST dataset
* Accuracy and loss visualization
* Prediction on unseen test images
* Model saving for future use

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib

## Dataset

The project uses the MNIST Handwritten Digit Dataset, which contains:

* 60,000 training images
* 10,000 testing images
* 28×28 grayscale images of handwritten digits

## Model Architecture

* Conv2D Layer (32 Filters, ReLU)
* MaxPooling2D Layer
* Conv2D Layer (64 Filters, ReLU)
* MaxPooling2D Layer
* Flatten Layer
* Dense Layer (128 Neurons, ReLU)
* Output Layer (10 Neurons, Softmax)

## Results

The CNN model successfully learns digit patterns and achieves high classification accuracy on the MNIST test dataset. The trained model can accurately predict handwritten digits from unseen images.

## Installation

```bash
pip install tensorflow numpy matplotlib
```

## Usage

Run the notebook in Google Colab or execute the Python script locally:

```bash
python handwritten_digit_recognition.py
```

## Output

* Model training and validation metrics
* Accuracy visualization graphs
* Handwritten digit predictions
* Saved trained model (`mnist_digit_recognition_model.h5`)

## Future Enhancements

* Real-time handwritten digit recognition
* Web application deployment using Flask
* Custom image upload and prediction
* Model optimization and hyperparameter tuning
