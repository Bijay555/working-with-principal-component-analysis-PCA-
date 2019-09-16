# Working-with-principal-component-analysis-PCA


# PCA

Summary of Approach

1. standardize the data
2. find covariance matrix of dataset
3. find the eigen vectors and eigen values from covariance matrix(we can use correlation matrix also which is normalized version of covariance matrix)
4. sort eigen values in descending order and choose k eigen vectors with highes eigen values or we can use scree plot for finding the number of k-value
5. construct projection matrix which is transpose version of your selected K eigen vectors (shape of matrix should be after transpose n_features X selected_PCs )
6. transform or project the original data on the projection matrix and you will get a matrix which has shape n_samples X selected_PCs


This consists of python code from Scratch to implement and understand PCA.
Also I have implemented with Scikit-Learn library.

# Scikit-learn
  Scikit-learn (formerly scikits.learn) is a free software machine learning library for the Python programming language. It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.

# Dataset
the dataset is one of common and most widely used datasets about flower- iris
the link to download dataset:
https://archive.ics.uci.edu/ml/datasets/Iris

