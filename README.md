# **Dog Breed Classification**
This project builds a convolutional neural network using transfer learning and TensorFlow Hub. The CNN is able to predict the breed of a dog shown in an image. 


**THE DATASET**

The dataset was obtained from Kaggle: https://www.kaggle.com/competitions/dog-breed-identification.

It contains a train set and a test set, each with images of 120 breeds of dogs.

**THE PROBLEM**

We want to create a CNN that can look at an image of a dog and correctly predict the breed of the dog. 

**THE MODEL**

We use mobilenet_V2, which is a pre-trained Single Shot MultiBox-based object detection model trained on Open Images V4 with ImageNet.
