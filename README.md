# PyTorch Image Classifier with Metal Performance Shaders for CIFAR-10

![PyTorch Logo](https://pytorch.org/assets/images/pytorch-logo.png)

## Overview

This Python project is an image classifier implemented in PyTorch and Jupyter Notebook, specifically designed to harness the power of Metal Performance Shaders for acceleration on MacBooks with Apple Silicon chips. The classifier is trained on the CIFAR-10 dataset, a widely-used dataset comprising 60,000 32x32 color images in 10 different classes. The objective is to classify these images into their respective categories using a Convolutional Neural Network (CNN).

### Features

- Utilizes Metal Performance Shaders for efficient computation on Apple Silicon chips.
- Implements a CNN architecture optimized for image classification.
- Trains and evaluates the model on the CIFAR-10 dataset.
- Provides a Jupyter Notebook for interactive exploration and experimentation.
- Offers an example of how to use the model for inference on custom images.

## Prerequisites

Before you can run this project, ensure you have the following dependencies installed:

- Python 3.x
- PyTorch (including Metal support for Apple Silicon)
- torchvision
- NumPy
- Jupyter Notebook
- CIFAR-10 dataset (automatically downloaded if not present)

## Installation

Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/shahman27/Deep-Learning-Image-Classifier.git
```

## Usage

1. **Training the Model**: Open the `CIFAR10 Image Classifier.ipynb` Jupyter Notebook and follow the step-by-step instructions to train the image classifier. This notebook provides a user-friendly interface for experimenting with different hyperparameters and model architectures.

2. **Evaluating the Model**: After training, you can also evaluate the model's performance using the provided Jupyter Notebook. This notebook will display accuracy metrics and visualizations to assess the model's effectiveness.

3. **Inference**: You can use the trained model for inference on custom images by adapting the code snippets provided in the notebook. Simply load the model and input your custom images for classification.

## Project Structure

Here's an overview of the project structure:

```
project-root/
│
├── data/
│   ├── cifar-10-batches-py/  # CIFAR-10 dataset (automatically downloaded)
│   └── ...
│
├── CIFAR10 Image Classifier.ipynb  # Jupyter Notebook for training, evaluation, and inference
│
├── README.md  # Project README (you are here)
│
└── requirements.txt  # Dependencies
```

## Acknowledgments

- The CIFAR-10 dataset is provided by [Canadian Institute for Advanced Research (CIFAR)](https://www.cifar.ca/).
- PyTorch and Metal Performance Shaders for macOS support.
- Inspiration from various CNN architectures for image classification.

Feel free to contribute, report issues, or make suggestions to enhance this image classifier!
