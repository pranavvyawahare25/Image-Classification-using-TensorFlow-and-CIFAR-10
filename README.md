# Image-Classification-using-TensorFlow-and-CIFAR-10
🖼️ TensorFlow-based Image Classification on CIFAR-10 dataset. Train a Convolutional Neural Network (CNN) for categorizing images. Easy-to-use with customization options. Explore and contribute!

# Image Classification with CIFAR-10 Dataset

![CIFAR-10 Image Classification](cifar10_image.png)

This repository contains a simple image classification model built with TensorFlow and trained on the CIFAR-10 dataset. The model classifies images into 10 different categories, including objects like airplanes, automobiles, birds, cats, and more.

## Getting Started

### Prerequisites

Make sure you have Python and TensorFlow installed on your machine. You can install TensorFlow using:


pip install tensorflow
Installation
Clone the repository: git clone https://github.com/your-username/image-classification-cifar10.git
cd image-classification-cifar10

Model Architecture
The image classification model uses a Convolutional Neural Network (CNN) with the following architecture:

Input Layer: Conv2D with ReLU activation
Hidden Layers: MaxPooling2D and Conv2D with ReLU activation
Fully Connected Layers: Flatten, Dense with ReLU activation
Output Layer: Dense with Softmax activation
