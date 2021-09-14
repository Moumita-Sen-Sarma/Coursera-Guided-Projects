# Coursera Guided Projects
#### 1. Creating Multi Task Models with Keras for Colored MNIST Dataset
#### 2. Neural Style Transfer using Pytorch
#### 3. Object Localization with TensorFlow
---------------------------------------------------------------------
## *Creating Multi Task Models with Keras for Colored MNIST Dataset*

Keras' functional API is used to create a multi output model which will be trained to learn two different labels given the same input example. The model will have one input but two outputs. A few of the shallow layers will be shared between the two outputs, a ResNet style skip connection is used in the model. In this task, MNIST dataset is used for classification purpose. Here, binary coloured (black and white) MNIST dataset is converted to RGB in a way that there will be a predominant colour in the final output and only red and green colours are used in this regard. Finally, the dataset samples are of shape 28x28x3, with predominant green/red colour.

- ### Sample of colored MNIST dataset:
![Alt text](Creating-Multi-Task-Models-with-Keras-for-Colored-MNIST-Dataset/images/data.png?raw=true "Title")

- ### The Convolutional Neural Network model (with skip connection):
![Alt text](Creating-Multi-Task-Models-with-Keras-for-Colored-MNIST-Dataset/images/model.png?raw=true "Title")

- ### Prediction Result on Test Data:
![Alt text](Creating-Multi-Task-Models-with-Keras-for-Colored-MNIST-Dataset/images/pred.png?raw=true "Title")

------------------------------------------
## *Neural Style Transfer using Pytorch*

![Alt text](Neural-Style-Transfer-using-Pytorch/images/styled_img.jpg?raw=true "Title")

Neural Style transfer is an optimization technique used to take a content and a style image and blend them together so the output image looks like the content image but painted in the style of the style image. 
In this project, an artistic style image is created using content and given style image. 
The content and style loss function are also calculated in this regard. These loss functions are minimized using optimization techniques to get an artistic style image that retains content features and style features.

### The key tasks in this project are:

- Load pretrained VGG-19 model.
- Extract content and style features.
- Create style and content loss function.
- Minimize the total loss to generate artistic style image.

-------------------------------------------
## *Object Localization with TensorFlow*
In this  project, TensorFlow's Keras API is used to create a **Convolutional Neural Network** which will be trained to **Classify** as well as **Localize Emojis** in images. 

Localization, in this context, means the position of the emojis in the images. This means that the network will have one input and two outputs. In Object Localization, it is considered that there is just one object in any given image, and the CNN model will classify and localize that object. 

The dataset used in this project, can be found [here](https://github.com/hfg-gmuend/openmoji/releases/latest/download/openmoji-72x72-color.zip) !
For training the model, custom callbacks and custom metrics in Keras are also used in this project. 
- ### Localization and Classifcation of Emojis
![Alt text](Object-Localization-using-Tensorflow/images/localization.jpg?raw=true "Title")
