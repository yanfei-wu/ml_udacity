# Classify Images using Neural Network 
## Overview 
Classified images from the CIFAR-10 dataset. The dataset was preprocessed (image normalization, label one-hot encoding), then trained a convolutional neural network with convolutional layer, max pool layer and fully connected layer on all the samples. The model was then evaluated on test samples. 

**Keywords:** classification, convolutional neural network, tensorflow 

## Libraries 
This project was done using **Python 3.5** with the following Python libraries: 
- TensorFlow 
- Numpy 
- Scikit-Learn 

## Data 
The [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset consists of 60000 32x32 colour images in 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck), with 6000 images per class. There are 50000 training images and 10000 test images. 

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks. 



