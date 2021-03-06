# Introduction

On my journey to understand deep learning, I tackled another challenge. This challenge involved the Iris Species dataset from
[Kaggle.](https://www.kaggle.com/uciml/iris)

The Iris flower data set is a multivariate dataset introduced by Ronald Fisher in his 1936 paper: [The Use of Multiple Measurements in Taxonomic Problems.](http://rcs.chemometrics.ru/Tutorials/classification/Fisher.pdf)
The dataset includes three Iris species (50 samples each), along with relevant attributes about each flower. 
It should be noted that the data is not linearly seperable. 

The data includes sepal length (in cm), sepal width (in cm), petal length (in cm), and petal width (in cm).


# The network
A deep learning approach was taken, utilizing the industry standard multilayer perceptron model (MLP).
The network employs the use of three hidden layers and three rectilinear activation functions. 
Categorical cross entropy was the loss (cost) function used to alter the weights during backpropagation. 
Dropout layers were implemented following each hidden layer to prevent overfitting of the data.

# Results
The model was able to achieve near 100% accuracy, training for a 100 epochs in less than 10 seconds on a GTX 760.

