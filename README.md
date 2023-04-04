K Nearest Neighbors Algorithm with Leave One Out Cross Validation

Overview
This project implements the k nearest neighbors algorithm using leave one out cross validation to determine the optimal value of k. The algorithm calculates the Euclidean distance between points to find the k nearest neighbors, and uses distance as the error metric.

Installation
To run this code, you will need to have Python 3 and the following libraries installed:

NumPy
matplot
scikit-learn

You can install these libraries using pip:
pip install numpy matplotlib scikit-learn

Usage
To use this code, you will need to have a dataset in .txt format with two columns representing the features and one column representing the target variable. 

The algorithm will output the optimal value of k, the accuracy of the model and decision boundary.

Algorithm Details
The k nearest neighbors algorithm is a classification algorithm that works by finding the k nearest data points to a given data point and assigning it the label of the majority of those neighbors. In this project, we use leave one out cross validation to find the optimal value of k, which involves leaving out one data point at a time and using the remaining data points to determine the optimal value of k.

Data
The dataset used in this project should be in txt/csv format with three columns representing the features and one column representing the target variable. The second column of the dataset is dropped during preprocessing.

Results
The output of the algorithm is the optimal value of k and the accuracy of the model. The accuracy is as the error of distance assuming the the
