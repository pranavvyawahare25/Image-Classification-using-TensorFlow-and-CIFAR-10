# Image Classification with TensorFlow and CIFAR-10

This repository contains a simple image classification project using TensorFlow and the CIFAR-10 dataset. The code demonstrates how to build a Convolutional Neural Network (CNN) to classify images into different categories.

## Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes. It is widely used for image classification tasks.

## Prerequisites

- Python 3.x
- TensorFlow (install via `pip install tensorflow`)

## Getting Started

- Clone the repository:

   ```bash
   git clone https://github.com/pranavvyawahare25/Image-Classification-using-TensorFlow-and-CIFAR-10


## Navigate to the project directory:

cd Image-Classification-using-TensorFlow-and-CIFAR-10

## Run the code:

python Image_Classification.py

Make sure you have Python and TensorFlow installed on your machine. You can install TensorFlow using:
- pip install tensorflow
- Installation
- Clone the repository: git clone https://github.com/pranavvyawahare25/Image-Classification-using-TensorFlow-and-CIFAR-10
- cd Image-Classification-using-TensorFlow-and-CIFAR-10

## Model Architecture
- The image classification model uses a Convolutional Neural Network (CNN) with the following architecture:
- Input Layer: Conv2D with ReLU activation
- Hidden Layers: MaxPooling2D and Conv2D with ReLU activation
- Fully Connected Layers: Flatten, Dense with ReLU activation
- Output Layer: Dense with Softmax activation

## Training
The model is trained for 10 epochs on the CIFAR-10 training set. You can experiment with different architectures, hyperparameters, and datasets to further improve its performance.

## Results
After training, the model achieved a test accuracy of 0.6995999813079834 on the CIFAR-10 test set.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

