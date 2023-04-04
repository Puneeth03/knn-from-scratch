K Nearest Neighbors Algorithm with Leave One Out Cross Validation

Overview
This project implements the k nearest neighbors algorithm using leave one out cross validation to determine the optimal value of k. The algorithm calculates the Euclidean distance between points to find the k nearest neighbors, and uses distance as the error metric.

Installation
To run this code, you will need to have Python 3 and the following libraries installed:

NumPy
pandas
scikit-learn
You can install these libraries using pip:

Copy code
pip install numpy pandas scikit-learn
Usage
To use this code, you will need to have a dataset in CSV format with two columns representing the features and one column representing the target variable. You can run the algorithm by running the following command in your terminal:

bash
Copy code
python knn.py <path/to/dataset.csv>
The algorithm will output the optimal value of k and the accuracy of the model.

Algorithm Details
The k nearest neighbors algorithm is a classification algorithm that works by finding the k nearest data points to a given data point and assigning it the label of the majority of those neighbors. In this project, we use leave one out cross validation to find the optimal value of k, which involves leaving out one data point at a time and using the remaining data points to determine the optimal value of k.

Data
The dataset used in this project should be in CSV format with two columns representing the features and one column representing the target variable. The second column of the dataset is dropped during preprocessing.

Results
The output of the algorithm is the optimal value of k and the accuracy of the model. The accuracy is calculated using the percentage of correct predictions over the total number of predictions.
