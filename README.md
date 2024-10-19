# Decision-tree-for-Iris-dataset
Training decision tree to classify unseen flower data set


# A Notebook to use Decision Tree Classifiers

This notebook shows how to train a decision tree to classify unseen instances. This notebook uses the [Iris dataset](https://archive.ics.uci.edu/dataset/53/iris). The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician, eugenicist, and biologist Ronald Fisher in his 1936 paper.


## Understanding the code

The code you are using here uses predefined functions from the sklearn library of machine learning primitives and from the graphviz library to generate visualizations. A few more details about the code:
* The variable "dataset" stores the name of text file that you input and is passed as an argument of the function "loadDataSet()".
* The variable "attributes" stores the names of all features. The variable "instances" stores the values of all features in the training set. The variable "labels" stores the labels of all instances.
* The variable "clf" stores a decision tree model, and it can be trained with "instances" and "labels". Once the model is trained, it can be used to predict unseen instances. We use a type of decision tree algorithm called CART (Classification and Regression Trees).
The variable "n_foldCV" stores the number of times of n-fold cross validation that you input.
* The function "cross_val_scores" assesses the accuracy scores of a decision tree model. Its inputs are "clf", "instances", "labels", "n_foldCV".
* The variable "scores" stores the accuracy of an n-fold cross validation of the model.
