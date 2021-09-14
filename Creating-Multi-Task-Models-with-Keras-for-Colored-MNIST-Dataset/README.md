# Creating-Multi-Task-Models-with-Keras-for-Coloured-MNIST-Dataset

Keras' functional API is used to create a multi output model which will be trained to learn two different labels given the same input example. The model will have one input but two outputs. A few of the shallow layers will be shared between the two outputs, a ResNet style skip connection is used in the model. In this task, MNIST dataset is used for classification purpose. Here, binary coloured (black and white) MNIST dataset are converted to RGB in a way that there will be a predominant colour in the final output and only red and green colours are used in this regard. Finally, the dataset samples are of shape 28x28x3, with predominant green/red colour.

## Sample of colored MNIST dataset:

## The Convolutional Neural Network model (with skip connection):

## Prediction Result on Test Data:
