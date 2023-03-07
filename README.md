# Image classification with CNN, pytorch on fashionMnist dataset
This project uses Convolutional Neural Networks (CNN) and PyTorch to perform image classification on the Fashion-MNIST dataset.

The Fashion-MNIST dataset is a collection of 70,000 images of clothing items in 10 different categories. The goal of this project is to build a model that can classify these images into categories they belong to.

Dataset

The Fashion-MNIST dataset consists of 60,000 training images and 10,000 testing images. Each image is a grayscale image with a resolution of 28x28 pixels.
The 10 different categories in the dataset are:

T-shirt/top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle boot

Models architecture


The project uses two models for image classification on the FashionMNIST dataset.
The first model is a simple one consisting of two linear layers with ReLU activation functions.

The second model is inspired by the CNN Explainer website(link: https://poloclub.github.io/cnn-explainer/) and uses convolutional layers to extract features from the input image.

The models are trained using the cross-entropy loss function and the Adam optimizer.

All code is contained in ImageClassificationWithFashionMNIST.ipynb file.
I recomend opening file with google colab since it is made in it and comments are better displayed.