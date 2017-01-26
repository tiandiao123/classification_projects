Name:Cuiqing Li

Submitted Date:9/17/2016

These are some projects which are used to implement classification machine learning algorithms and their applications! 

###Project:
## Implementing binary decision trees
The goal of this notebook is to implement your own binary decision tree classifier. You will:
    
* Use SFrames to do some feature engineering.
* Transform categorical variables into binary variables.
* Write a function to compute the number of misclassified examples in an intermediate node.
* Write a function to find the best feature to split on.
* Build a binary decision tree from scratch.
* Make predictions using the decision tree.
* Evaluate the accuracy of the decision tree.
* Visualize the decision at the root node.

**Important Note**: In this assignment, we will focus on building decision trees where the data contain **only binary (0 or 1) features**. This allows us to avoid dealing with:
* Multiple intermediate nodes in a split
* The thresholding issues of real-valued features.

This assignment **may be challenging**, so brace yourself :)

# Identifying safe loans with decision trees

The [LendingClub](https://www.lendingclub.com/) is a peer-to-peer leading company that directly connects borrowers and potential lenders/investors. In this notebook, you will build a classification model to predict whether or not a loan provided by LendingClub is likely to [default](https://en.wikipedia.org/wiki/Default_(finance)).

In this notebook you will use data from the LendingClub to predict whether a loan will be paid off in full or the loan will be [charged off](https://en.wikipedia.org/wiki/Charge-off) and possibly go into default. In this assignment you will:

* Use SFrames to do some feature engineering.
* Train a decision-tree on the LendingClub dataset.
* Visualize the tree.
* Predict whether a loan will default along with prediction probabilities (on a validation set).
* Train a complex tree model and compare it to simple tree model.

# Decision Trees in Practice

In this assignment we will explore various techniques for preventing overfitting in decision trees. We will extend the implementation of the binary decision trees that we implemented in the previous assignment. You will have to use your solutions from this previous assignment and extend them.

In this assignment you will:

* Implement binary decision trees with different early stopping methods.
* Compare models with different stopping parameters.
* Visualize the concept of overfitting in decision trees.

# Exploring Ensemble Methods

In this assignment, we will explore the use of boosting. We will use the pre-implemented gradient boosted trees in GraphLab Create. You will:

* Use SFrames to do some feature engineering.
* Train a boosted ensemble of decision-trees (gradient boosted trees) on the LendingClub dataset.
* Predict whether a loan will default along with prediction probabilities (on a validation set).
* Evaluate the trained model and compare it with a baseline.
* Find the most positive and negative loans using the learned model.
* Explore how the number of trees influences classification performance.

# Boosting a decision stump

The goal of this notebook is to implement your own boosting module.

**Brace yourselves**! This is going to be a fun and challenging assignment.


* Use SFrames to do some feature engineering.
* Modify the decision trees to incorporate weights.
* Implement Adaboost ensembling.
* Use your implementation of Adaboost to train a boosted decision stump ensemble.
* Evaluate the effect of boosting (adding more decision stumps) on performance of the model.
* Explore the robustness of Adaboost to overfitting.



Notice： The project assignment is from the Coursera class (machine learning) which was conducted by University of Washington (Seattle).