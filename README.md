# CIFAR-10 Image Classification using CNN

## Project Overview
This project was developed as part of my university coursework in Artificial Intelligence. It focuses on building and training a Deep Convolutional Neural Network (CNN) to automate image classification using the CIFAR-10 dataset. The primary goal was to develop a model capable of recognizing 10 distinct object categories while maintaining high generalization performance.

## Tech Stack
* Language: Python 3.x
* Deep Learning: TensorFlow, Keras
* Data Processing: NumPy, Scikit-learn
* Visualization: Matplotlib

## Key Features
* CNN Architecture: Sequential model featuring Conv2D, BatchNormalization, and Dropout layers to ensure training stability and mitigate overfitting.
* Data Augmentation: Implemented ImageDataGenerator for real-time image transformations, enhancing the model's robustness.
* Advanced Training Pipeline: Integration of Keras callbacks including EarlyStopping, ReduceLROnPlateau, and ModelCheckpoint for optimized training.
* Performance Analysis: Detailed evaluation using Confusion Matrices to identify per-class accuracy and misclassification patterns.

## Results
The model demonstrates strong generalization capabilities on the test set due to the effective use of regularization and image augmentation techniques.
