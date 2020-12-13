1. A special case of K-Fold cross-validation is Leave-One-Out cross- validation where K (i.e., the number of folds/subsets) is equal to the size of the training dataset. In each iteration, one training data point is used as the validation set. 
Implement a Leave-One-Out cross-validation (CV) function for your KNN regressor:
cv(train.data, train.label, K, numFold=?) which takes the training data and their labels (continuous values), K value, the number of folds, and returns errors for different folds of the training data.

2. Using the training data run your Leave-One-Out CV. Change the value of K=1,..,15 in your KNN regressor, and for each K compute the average of error values you have got for folds.
