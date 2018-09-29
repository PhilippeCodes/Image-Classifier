# Image-Classifier

We will be building machine learning models to classify images fromt the CIFAR-10 data set as part of the EPFL Applied Machine Learning Course (Project 4). The goal is to train and evaluate different models using the train set and make predictions for the pictures of the test set. Should the person who is looking at this analysis have any questions or suggestions, do not hesitate to contact me.

## The Data

The cifar4-train.npz file contains data for 5,000 images of cars, trucks, shipps and airplanes. 
The file contains the following arrays:
- pixels: input matrix with the flat vectors of pixels (5000, 3072)
- labels: output vector of labels (5000,)
- names: class names (4,)
- overfeat: input matrix with high-level features extracted by OverFeat (5000, 4096)

The overfeat array contains pre-extracted features using the OverFeat (Object Recognizer, Feature Extractor) convolutional neural network. The network was developed by the CILVR lab from the New York University and participated in the ImageNet 2013 competition.

The goal of this project is to use this set of high-level features to test the different classification methods from the course (decision trees, SVMs and so on) and compare the results to your own implementation of a ConvNet trained on the raw 32 by 32 RGB images.

