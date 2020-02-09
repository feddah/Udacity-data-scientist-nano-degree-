# Data Scientist Nanodegree
Convolutional Neural Networks
Project: Write an Algorithm for a Dog Identification App
Classify images of dogs according to their breed.
Article : https://medium.com/@fdalthaqeel/convolutional-neural-networks-project-dog-identification-app-4cf42312bb68

Feddah Alotaibi 


# Project Overview
The project aims to classify images of dogs according to their breed using deep learning neural network as part of Udacity’s Data Scientist Nano Degree.  In this project, I developed an algorithm that could be used as part of a mobile or web app.  The code will accept any user-supplied image as input.  If a dog is detected in the image, it will provide an estimate of the dog's breed.  If a human is detected, it will provide an estimate of the dog breed that is most resembling.  The image below displays potential sample output of your finished project.

## To run this code on your local computer, you need to download the following:

- Dog dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.
- Human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw.
  these two files can be found in udacity nano degree data scientist final project 
- Human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw.
- VGG-16 bottleneck features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.
- Inception bottleneck features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

## This project requires python libraries installed:
NumPy, Pandas, matplotlib, scikit-learn, keras, OpenCV, Matplotlib, Scipy, Tensorflow, Skimage, IPython Kernel, glob, ImageFile  

## Main files in the repository include the following:
- dog_app.ipynb where the possible solution will found.

- bottleneck_features when you Pick one of the above architectures, download the corresponding bottleneck features, and store the downloaded file in the bottleneck_features/ folder in the repository.

- images where you will find the images for testing your model 

- saved_models where you will find the pre trained model used 

## Data Description and anlysis 
There are 133 total dog categories in dataset of 8351 dog images 
Splitting the data into three sets/  
There are 6680 training dog images. 
There are 835 validation dog images. 
There are 836 test dog images.

## The steps provided by Udacity, as follows:
Step 0: Import Datasets
Step 1: Detect Humans
Step 2: Detect Dogs
Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)
Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)
Step 6: Write your Algorithm
Step 7: Test Your Algorithm
In this project I have used Keras to build our Convolutional Neural Network (CNN) to make the dog predictions, though it would also be possible to use PyTorch, which we have used in a previous project in this Data Science nanodegree to classify flower species from a given image.

## Result 

The best performing model was CNN using Inception pre trained model achiveing accuracy of almost 80% 

## Conclusion: 
the model obtained nearly 80% Which is good, however there are more area that would have improved the model if taking into consideration. 
I think the model would have been improved by training more data. Also, performing data augmentation through the use of rotation, rescale and other transformation and also to prevent overfitting. Optimizing number of layers would have improved the neural network as well
In addition to performing hyperparameter optimization. Considering the above I’m sure we could increase the testing accuracy of the model to above 90%.


