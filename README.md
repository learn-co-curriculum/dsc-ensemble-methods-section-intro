
# Introduction

## Introduction
This lesson summarizes the topics we'll be covering in section 24 and why they'll be important to you as a data scientist.

## Objectives
You will be able to:
* Understand and explain what is covered in this section
* Understand and explain why the section will help you to become a data scientist

##  Extensions to Linear Models

Unfortunately, not every continuous variable can be predicted effectively using a straight line (a linear model). Imagine the relationship between your 5k time as a runner and how many hours a week you train. At the very least the improvements in your time are going to trail off with additional training (going from 0 -> 10 hrs training a week is going to have way more impact than going from 60 -> 70 hrs). And the chances are that at some point in time, you'll overtrain and additional training will actually degrade your performance. You could certainly model the relationship between weekly training hours and 5k time with a straight line, but for some values of weekly training time the accuracy of the prediction would probably be extremely low.

In this section, we introduce a number of concepts to help you to make predictions where there is not a linear relationship between the predictor and target variables.

### Interactions

We start by introducing the concept of interactions - where two or more variables interact in a non-additive manner when affecting a third variable. We look at why they are important and how to account for them.

### Polynomial Regression

We then introduce higher order equations for solving regressions. A linear expression can be described by an equation in the form of y = mx + b. A polynomial expression brings in higher powers of x (squared, cubed, etc). By allowing for equations containing higher order terms it's quite possible that you'll be able to better fit a curve to your data set, better predicting future values.

### Bias-Variance Tradeoff

While polynomail regression can improve the accuracy of your models, they also exacerbate the risk of over-fitting the data, making your model extremely accurate for the training set but completely inaccurate for any future data points the model wasn't trained on. We take some time to look at the concept of bias-variance trade off and how it relateds to underfitting and overfitting data sets.

### Ridge and Lasso Regression

Next up, we introduce the idea of Ridge and Lasso regressions - two techniques that penalize more complex models to reducing overfitting for polynomial regressions.

### AIC and BIC

Finally we introduce the concepts of AIC and BIC - two tools for comparing potential models to help better select between them. We then round out the section with a lab that gives you a chance to work with a number of the concepts that we introduced.


## Summary

In the last section of module 2, we introduce a range of additional techniques you can use for better predicting variables when a simple linear model is insufficient.

