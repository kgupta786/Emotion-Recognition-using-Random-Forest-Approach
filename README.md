# Emotion-Recognition-using-Random-Forest-Approach
This repo contains all the necessary python files in order to analyse the emotions of a person through its image

Python Libraries Used here are:

1. sklearn
2. numpy
3. pandas
4. skimage

Steps to evaluate the Recognition program in Python:

1. Import all the above necessary libraries
2. Read the dataset from Kaggle website for Face Emotion Recognition known as 'fer2013.csv'
3. Get the X-Values and Y-Values and split into Training and Testing Dataset
4. Do some Feature Scaling if necessary.
5. Use RandomForestClassifier to fit your model and after that you can check its accuracy over the testing data
6. Now Take any image, convert into grayscale of size 48*48 pixels and use it as X-features and finally predict the emotions




