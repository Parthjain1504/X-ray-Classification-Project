# X-ray-Classification-Project
In this project I have used CNN model which is used for classification 
# Pneumonia Detection from Chest X-Rays using CNN and AlexNet

This project focuses on binary classification of chest X-ray images to detect whether a patient has pneumonia or not. Two convolutional neural network (CNN) models were developed and evaluated:

- A custom CNN model
- And a pretrained model (alexnet)

 Dataset

The dataset used is from [Kaggle: Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia), which includes chest X-ray images categorized into:
a) Normal
b) Pneumonia
It is divided into `train`, `test`, and `val` directories.

 Models Used
 1. Custom CNN Model
A basic convolutional neural network architecture built from scratch using TensorFlow/Keras. It consists of several convolutional and pooling layers followed by fully connected layers.
Accuracy: 80%

2. AlexNet 
Used a pretrained AlexNet architecture, fine-tuned for binary classification on the pneumonia dataset.
Accuracy: 89%

 Technologies & Libraries
a) Python
b) TensorFlow / Keras
c) NumPy, Matplotlib
d) Google Colab / Kaggle Notebooks
