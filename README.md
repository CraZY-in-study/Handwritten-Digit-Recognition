# Handwritten-Digit-Recognition

## Problem defined:
The problem is to recognize handwritten digits from the MNIST dataset, which is assumed to have 5 styles of handwriting and follows a Gaussian Mixture Model (GMM) distribution.

## Data Preparation:
The MNIST dataset, originally consisting of 784 dimensions, was reduced to 543 dimensions using Principal Component Analysis (PCA), preserving 99% of the variance. The dataset was then divided into 5 classes using a Bayesian classifier.

## Data Process:
A Convolutional Neural Network (CNN) model was used to recognize the handwritten digits. The model was trained on the classified dataset.

## Data Analysis:
The model showed excellent fitting results on the training set. However, it did not perform as well on the test set. This discrepancy might be due to the small size of the classified dataset.

## Conclusion:
While the classification of the dataset and the use of the CNN model resulted in good performance on the training set, the model's performance on the test set was not as good. This suggests that the size of the classified dataset might be a limiting factor. Future work could explore methods for expanding the classified dataset or adjusting the model to better handle smaller datasets.
