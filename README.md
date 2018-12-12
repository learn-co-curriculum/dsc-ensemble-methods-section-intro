
# Introduction

## Introduction
This lesson summarizes the topics we'll be covering in section 32 and why they'll be important to you as a data scientist.

## Objectives
You will be able to:
* Understand and explain what is covered in this section
* Understand and explain why the section will help you to become a data scientist

## Ensemble Methods

The idea of ensemble methods is to bring together multiple models to use them to improve the quality of your predictions when compared to just using a single model. In many real world problems and kaggle competitions, ensemble methods tend to outperform any single model.

### Ensemble Methods

We start the section by providing an introduction to the concept of ensemble methods, explaining how they take advantage of the delphic technique (or "wisdom of crowds") where the average of multiple independent estimates is usually more consistently accurate than the individual estimates.

We also provide an introduction to the idea of bagging (Bootstrap AGGregation).

### Random Forests

We then look at random forests - an ensemble method for decision trees that takes advantage of bagging and the subspace sampling method to create a "forest" of decision trees that provides consistently better predictions than any single decision tree.

### GridsearchCV

In the last section we introduced some of the common hyperparameters for tuning a decision tree. In this lesson we look at how you can use GridsearchCV to perform an exhaustive search across multiple hyperparameters and multiple possible values to come up with a better performing model.

### Gradient Boosting and Weak Learners

Next up, we introduce the concept of boosting which is at the heart of some of the most powerful ensemble methods such as Adaboost and Gradient Boosted Trees. 

### XGBoost

We then round out the section by introducing XGBoost (eXtreme Gradient Boosting) - the top gradient boosting algorithm currently in use.




## Summary

You will often find youself using a range of ensemble techniques to improve the performance of your models, so this section will provide you with experience with techniques that will help you to improve the quality of your modeling.

