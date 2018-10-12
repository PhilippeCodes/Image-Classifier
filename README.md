# Image-Classifier

As part of the EPFL Applied Machine Learning Course (Project 4) we will build images classifiers for the CIFAR-10 data set.
we will build and evaluate various machine learning models and use our best model to make predictions for the pictures of the test set. Should the person who is looking at this analysis have any questions or suggestions, do not hesitate to contact me.

## The Data

The cifar4-train.npz file contains data for 5,000 images of cars, trucks, ships and airplanes. 
The file contains the following arrays:
- Pixels: input matrix with the flat vectors of pixels (5000, 3072)
- Labels: output vector of labels (5000,)
- Names: class names (4,)
- Overfeat: input matrix with high-level features extracted by OverFeat (5000, 4096)

The overfeat array contains pre-extracted features using the OverFeat (Object Recognizer, Feature Extractor) convolutional neural network. The network was developed by the CILVR lab from the New York University and participated in the ImageNet 2013 competition.

## Classifiers

- k-Nearest-Neighbor
- Decision Tree
- RandomForest
- LogisticRegression
- SVM Linear Kernel
- SVM RBF Kernel
- Multilayer Neural Network
- Convolutional Neural Network

 We will be using grid search with cross-validation to tune our hyperparameters


