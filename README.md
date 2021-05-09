# Bank-churn-prediction-and-modelling
Given a Bank customer, build a classifier model which can determine whether they will leave in the next 6 months or not.


The following are the problems with the dataset:
- First problem is imbalanced dataset and we define three methods of resampling:
  * **overSampling:** In this method add samples in lower class and make it equal to class2, the disadantage is : we can make overfitting to our model.
  * **underSampling:** In this method add to lower class more samples repeted samples to lower class to be equaled to another class disadventage:that we are lossing more important information.
  * **combination oversampling and undersampling(the best):** This method is the best one because it combine the advantage of first method and advantage second method add and remove samples to be nearly equal to each other.
- We choose the classifier and feed our resampling data to fitting and training on it, then we choose the higher one based on metrics and we choose metrics specified to deal with imbalanced data like: f1 score, kappa score, precision, recall then we create grid search to selected most powerful parameters to classifier.then create confusion and roc curve to see the final result.

