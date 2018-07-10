# ANNBasics

## Churn prediction using ANN

This project demonstatrate the use of Keras library to build ANN to predict the churn of the Bank Customer.

The dataset contains the details of 10,000 customers. From all the given features, 11 most relevant features are taken and a model is built with 5 hidden layers each with 6 nodes. The activation function used is Rectified Linear Unit or 'relu' for the hidden layers and Sigmoid for the output layer. Accuracy metric is used to evaluate Training Set.

Output is positively classified if the output of the Sigmoid function is >0.5.

Test set accuracy is checked with the help of confusion matrix.

Here with above parameters, training set and test set accuracy is found around 86%.
