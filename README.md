# Sign Recognition using LSTM and CNN

This project implements sign recognition from a custom dataset using two deep learning approaches:

- **LSTM Model:** Utilizes sequential keypoint data for recognizing sign language gestures.
- **CNN Model:** Uses image data to classify signs through convolutional neural networks.

## Dataset

A custom dataset of sign language images and corresponding keypoints, collected and preprocessed for training and evaluation.

## Features

- Sequence modeling with LSTM for temporal gesture recognition.
- Image-based classification using CNN.
- Comparison of both models for performance and accuracy.

## How to Run

1. Prepare the dataset folder structure as required.
2. Train and evaluate the LSTM model on keypoint sequences.
3. Train and evaluate the CNN model on sign images.
4. Test on new sign inputs for recognition.

## Requirements

- Python 3.9/3.10
- TensorFlow / Keras  
- OpenCV  
- NumPy  
