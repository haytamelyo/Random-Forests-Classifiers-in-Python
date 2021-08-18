# Random Forests Classifiers in Python

## Random forests 

Random forests is a supervised learning algorithm. It can be used both for classification and regression. It is also the most flexible and easy to use algorithm. A forest is comprised of trees. It is said that the more trees it has, the more robust a forest is. Random forests creates decision trees on randomly selected data samples, gets prediction from each tree and selects the best solution by means of voting. It also provides a pretty good indicator of the feature importance.
Random forests has a variety of applications, such as recommendation engines, image classification and feature selection. It can be used to classify loyal loan applicants, identify fraudulent activity and predict diseases. It lies at the base of the Boruta algorithm, which selects important features in a dataset.

## How does the algorithm work?

It works in four steps:
1.	Select random samples from a given dataset.
2.	Construct a decision tree for each sample and get a prediction result from each decision tree.
3.	Perform a vote for each predicted result.
4.	Select the prediction result with the most votes as the final prediction.


