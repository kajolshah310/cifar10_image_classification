# CIFAR10 Image Classification

## Description
This repository focuses on classifying images in the CIFAR10 dataset using a fully connected neural network implemented with Keras. The objective is to develop a classification model that can accurately classify images into 10 different classes, including airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

The CIFAR10 dataset is a widely used benchmark dataset in computer vision. It consists of 60,000 32x32 color images, equally divided into 10 classes, with 6,000 images per class. The dataset is split into 50,000 training images and 10,000 test images. Each image is associated with a corresponding label indicating the class it belongs to.

## Dataset
The CIFAR10 dataset is available in the keras.datasets module. It provides a convenient way to load the dataset without manually downloading or preprocessing the data. The dataset is already split into training and test sets, with images represented as NumPy arrays.

## Approach
The project involves the following steps:
1. Loading and preprocessing the CIFAR10 dataset using the keras.datasets module.
2. Exploratory data analysis to understand the distribution and characteristics of the dataset.
3. Implementing a fully connected neural network using Keras, a high-level deep learning library.
4. Model training and evaluation using the training set, followed by testing on the unseen test set.
5. Analysis of model performance using evaluation metrics such as accuracy, precision, recall, and F1 score.
6. Visualization of the classification results and examination of misclassified images.

## Usage
1) Clone the repository to your local machine using the following command:
```
git clone https://github.com/kajolshah310/cifar10_image_classification.git
```
2) Open the cifar10_image_classification.ipynb file in Jupyter Notebook or any other compatible IDE.

3) Install the required packages and dependencies mentioned in the notebook, if necessary.

4) Execute the code and follow along with the implementation of the CIFAR10 image classification model.

Feel free to modify the code, experiment with different neural network architectures or hyperparameters, or explore additional techniques to improve the classification accuracy.

## References
1) Dataset: CIFAR10 from keras.datasets

## License
This repository is licensed under the MIT License. Feel free to use the code and the models for your own projects or research.
