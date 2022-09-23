# ANN-on-Iris
Dataset used: Iris Dataset

Library Used: pandas, numpy, sklearn, keras

Steps:

Importing libraries that will be used

Importing dataset
Figure out how many labels are present in the dataset
Associating numeric values with each type of labels present
Splitting dataset between features and labels
Normalizing features within a range of 0 to 1 for better processing
Splitting dataset into training (80%) and testing (20%) sets
Converting labels to one-hot vectors
Using Sequential() from keras to build layers
Using ReLU as activation for the first two layers & Softmax for the last layer
Using categorical Cross Entropy as loss and adam as optimizer
Fitting model and predicting for test values
Finding Accuracy
