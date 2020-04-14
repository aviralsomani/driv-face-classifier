# Aviral Somani: DrivFace Dataset Classifier
CS 3891 - Final Project Spring 2020
## Midway Report
My project utilizes the DrivFace dataset from the UCI Machine Learning Repository. This is a database of image sequences of subjects taken while they are driving in real scenaiors. It contains 4 drivers across numerous instances, with two men and two women. There are three classifications, looking right, looking left, and frontal, which are self-explanatory. In this project, I hope to train a convolutional neural network to classify these images with a great degree of accuracy.

I have been able to set up a [colab notebook](https://github.com/aviralsomani/driv-face-classifier/blob/master/AviralSomani_FinalProject.ipynb) where I can pipeline the data from the UCI Repository using wget, and then use python to separate the subjects into separate directories by label. I have also been able to split up these subjects into training and validation datasets and train preliminary convolutional nets using Keras. I hope to improve upon this performance, but it at least means that my remaining work is on the machine learning side and not as much the data infrastructure side.

Moving forward, I would like to tweak the network architecture and hyperparameters in order to train a highly performant model and use k-fold cross-validation to minimize problems with overfitting. 
