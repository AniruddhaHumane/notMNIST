# notMNIST
a project to preprocess and train a simple logistic regression model on notMNIST dataset

the dataset is obtained from following link
http://yaroslavvb.com/upload/notMNIST/

MNIST is too easy. Convolutional nets can achieve 99.7% on MNIST easily, and similarly, even classic ML algorithms can achieve 97%.

If you take a look at the dataset you may find it a bit harder than the typical MNIST dataset as this data is processed to look more like real world letters. It is a set of training and test images of letters from A to J on various typefaces.

This jupyter notebook is referenced from the self-evaluated Assignment of udacity's deep learning course.
https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/udacity/1_notmnist.ipynb

on training an out of the box logistic Regression model from scikit learn on various sample sizes it's accuracy increases from 62% to 85%
