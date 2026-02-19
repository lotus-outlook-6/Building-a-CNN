# Convolutional Neural Network (CNN) Implementation
 
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)
![Status](https://img.shields.io/badge/Status-Complete-green)

## 📖 Overview

This repository contains a Jupyter Notebook implementation of a Convolutional Neural Network (CNN) for image classification. The architecture and logic follow the principles outlined in the [SuperDataScience Ultimate Guide to CNNs](https://www.superdatascience.com/blogs/the-ultimate-guide-to-convolutional-neural-networks-cnn).

The goal of this project is to demonstrate how deep learning models extract features from input images to classify them with high accuracy.

## 🧠 Architecture Explained

Following the guide, the model is built using the following four main steps:

1.  **Convolution:** Applying feature detectors (filters) to the input image to create Feature Maps. This preserves the spatial relationship between pixels.
2.  **Max Pooling:** Down-sampling the feature maps to reduce dimensionality and computation while preserving the most important information (spatial invariance).
3.  **Flattening:** Converting the 2D pooled feature maps into a single long continuous linear vector.
4.  **Full Connection:** Feeding the flattened vector into a fully connected Artificial Neural Network (ANN) to perform the final classification.

## 📂 Project Structure

```text
├── data/                   # Dataset images (Train/Test sets)
├── notebooks/              # Jupyter Notebooks
│   └── cnn_model.ipynb     # Main implementation file
├── models/                 # Saved model weights (.h5 files)
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
