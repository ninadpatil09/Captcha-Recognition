# Captcha-Recognition

![captcha](https://github.com/ninadpatil09/Captcha-Recognition/assets/60342946/5854f3c1-086a-408e-a323-891ca4228cbe)

## Overview

This project aims to recognize characters within CAPTCHA images using deep learning techniques. CAPTCHA, or Completely Automated Public Turing test to tell Computers and Humans Apart, is a challenge-response test commonly used in computing to determine whether or not the user is human.

## Contents
#### Loading and Preprocessing Data
  - Reading CAPTCHA images from the provided directory.
  - Visualizing sample images and understanding the dataset.
  - Preprocessing images for better model training.
#### Training the Model
  - Constructing a convolutional neural network (CNN) model for character recognition.
  - Compiling the model with appropriate loss function and optimizer.
  - Training the model on the prepared dataset.
#### Evaluating the Model Performance
  - Assessing the trained model's performance on the test dataset.
  - Calculating test loss and accuracy.
#### Visualizing Training Progress
  - Plotting graphs to visualize training and validation accuracy over epochs.
  - Plotting graphs to visualize training and validation loss over epochs.
#### Predicting with New Images
  - Implementing a function to predict characters in new CAPTCHA images.
  - Demonstrating the prediction on sample images.

## Conclusion
The model achieved a satisfactory accuracy of around 90% on the test dataset, indicating its capability to recognize characters in CAPTCHA images effectively. Further improvements could be made by exploring advanced CNN architectures, increasing the diversity of training data, or fine-tuning hyperparameters.
