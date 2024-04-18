# **DOG BREED CLASSIFICATION**
This repository contains a deep learning project in which transfer learning was used to create a model that can predict the breed of dog shown in an image. 
This represents a classification problem, in which the purpose of the model is to label an image based on the values of the pixels it contains. 
For this project, the employed dataset comprises 10222 images of dogs of 120 possible breeds that were used to train a pre-trained convolutional neural network.

As mentioned previously, transfer learning was leveraged to create the prediction model. Transfer learning is a popular technique in Machine Learning that consists in
taking a model developed for a problem and applying it to another problem. Of course, the problems must be similar for the model to leverage the previously learned information. 
In this project, MobileNet V2, an SSD-based object detection model trained on Open Images V4, was used to detect the dog breeds in images. The advantage of transfer learning is
that it greatly reduces computing time and allows for training on smaller datasets. 

## Steps for the Project

* Importing the images and labels and creating batches to feed to the model for training
* Creating a model using transfer learning through TensorFlow Hub and TensorFlow
* Training and testing the model
* Visualizing the results
* Using the model on a custom image
