# Deep Learning Project: Image Classification with CIFAR-10 Dataset

## Overview

This project demonstrates the use of a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The dataset contains 50,000 training images and 10,000 testing images in 10 different classes, namely:
1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

Our model consists of three Conv2D layers followed by MaxPooling2D layers for feature extraction. We then flatten the output and pass it through Dense layers for classification.

## Dependencies

- > later than Python 3.8
- > later than TensorFlow 2.8.0
- > Keras 

## How to Run

1. Install the required packages:

```bash
pip install tensorflow keras
```

2. Results
The results will be printed in the console after every epoch. They include the accuracy and loss for both training and validation data.

3. Future Work
This is a simple model for experiment purposes. There are a lot of potential improvements, such as:  

- Hyperparameter tuning
- Using a more sophisticated architecture
- Implementing data augmentation
- Applying regularization techniques to prevent overfitting





