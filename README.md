# Bank-churn-prediction-and-modelling
Given a Bank customer, build a classifier model which can determine whether they will leave in the next 6 months or not.

## Churn Prediction
It is the technique using which we can predict or detect the customers who are likely to cancel their subscription in the near future.

There are 3 ways using which businesses can generate revenue:
* Upsell to existing customers.
* Acquire new customers.
* Increase a customer retention.

Churn prediction helps in focusing in the third point i.e. increase a customer retention in which we can predict the churn rate or those customers who are going to cancel the subscription and then take pro-active action before they leave so that they stay in business.

## Description:

In this project we will be creating a model using the bank past churn data of the cutomers and predict the future churn rate of customers so that we can know which cateogry of customer has has high churn rate and take a pro-active action inorder to make them stay in business.

#### What is churn rate?

According to wikipedia, The churn rate is the rate at which customers stop doing business with an entity. It is most commonly expressed as the percentage of service subscribers who discontinue their subscriptions within a given time period.

# Dataset

First problem is the imbalanced dataset and we define three methods of resampling:
  * **overSampling:** In this method add samples in lower class and make it equal to class2, the disadantage is : we can make overfitting to our model.
  * **underSampling:** In this method add to lower class more samples repeted samples to lower class to be equaled to another class disadventage:that we are lossing more important information.
  * **combination oversampling and undersampling(the best):** This method is the best one because it combine the advantage of first method and advantage second method add and remove samples to be nearly equal to each other.
