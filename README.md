# Nearest-Neighbor-Classifier-Implementation

The objective of this notebook is to do an implementation of one of the simplest machine learning methods: [Nearest neighbor classifier](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm). 

Given a training set of n training examples each with d features and known class label, the nearest neighbor classifier works by finding the eculidean distance of a test example whose class label is not known with all examples in the training set and assigning the label of the nearest training example to the test example. Essentially, it predicts the class label of a test example based on the label of its closest (or least dissimilar) training example. A more generic variant of the classifier, called a k-nearest neighbor (kNN) classifier works by predicting the label of a test example based on majority of k-nearest training examples. The nearest neighbor classifier thus becomes a special case of this classifer with k=1.

### NB: The following tasks have been put together by the CS909 Data Mining Module on my Masters programme - the solutions however are my own:

1. Generating and visualizing some (toy) data
2. Implementing a distance function
3. Implementing a nearest neighbor classifier function and generating predictions for test data
4. Implementing a function to calculate accuracy
5. Using built-in (sklearn) implementation of k-nearest neighbor classifier
