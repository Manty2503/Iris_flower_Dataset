# Iris_flower_Dataset

Given with Iris flower dataset file. The file Iris.csv consists of 150, 4-dimensional data
which includes 50 samples from each of the three species of Iris (Iris setose, Iris virginica and Iris
versicolor). Column 1 to 4 of the given file are the four features (attributes) that were measured
from each sample: the length and the width of the sepals and petals (in centimetres) respectively.
Column 5 is the class label (species name) associated with each of the samples of Iris flower.

We had to reduce the data into 2-dimensional data using PCA and then partition (cluster) the
reduced dimensional data using different clustering techniques. While performing the PCA, ignore
the target column.

Target Attribute was to be used to calculate the Purity Score.

The code:
* Loads the dataset into the Spyder Enviornment.
* Imports the Unsupervised Learning Models like k-means, GMM and DBSCAN.
* We form Clusters and then we label them for each of the model seperately and check the purity score for each model.
