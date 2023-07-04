# Image Classification on CIFAR 10
In this project, classification of images in the CIFAR-10 dataset will be done using machine learning techniques.  I have used the following models and their variations:
1. Logistic Regression
2. Support Vector Machines (SVM)
3. Convolutional Neural Networks (CNN)

# About the dataset
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
Link to dataset: https://www.cs.toronto.edu/~kriz/cifar.html 

# Data Modeling
## Logistic Regression
Logistic Regression is a baseline model for this dataset. To preprocess the data, we performed:
1. Normalization using Normalizer()
2. Regularization using L2 penalty

## Support Vector Machine
Support Vector Machine (SVM) is a Machine Learning technique that is used for classification as well as regression. The SVM operates by finding a hyperplane in the N-dimensional space that can distinctly qualify the data points, where N is the number of features. The goal is to maximize the distance between the data points of the classes. 

To preprocess the data for the SVM model, we performed the following steps:
1. Normalization using Normalizer()
2. Scaling using StandardScaler()
Finally, we train the SVM model using polynomial kernel.

## Convolutional Neural Network (CNN)
Convolutional Neural Network (CNN) is a deep learning technique that takes an image as an input, assigns weights and biases to various aspects of the image to differentiate from one another. CNN is a very suitable technique for a complex task like image classification and can yield very high accuracy even on unseen data.

