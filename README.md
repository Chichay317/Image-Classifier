# Image-Classifier

A deep learning model that classifies images as either cats or dogs using convolutional neural networks (CNNs).

Features
1. Loads and preprocesses image dataset
2. Preprocesses images using Keras ImageDataGenerator with pixel rescaling and batch generation
3. Implements data augmentation techniques like rotation, shifting, shearing, zooming, and flipping to improve model generalization
4. Builds a Convolutional Neural Network (CNN) using multiple Conv2D, MaxPooling2D, Flatten, and Dense layers
5. Uses ReLU activation for feature extraction and Sigmoid activation for binary classification
6. Compiles the model with Adam optimizer and binary cross-entropy loss for binary outcome learning
7. Trains the model for 15 epochs with batch size 128 and monitors performance using validation accuracy and loss
8. Predicts on unseen test images and displays model confidence (percentage likelihood of cat or dog)
9. Evaluates performance with overall accuracy and determines if it passes the challenge threshold (≥63%)
