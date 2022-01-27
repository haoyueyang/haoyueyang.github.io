---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests fall into two main areas: applying machine learning and statistical learning methods to solve problems concerning social good and financial optimization, and developing improvements of machine learning methodology for certain problems, such as highly correlated features and imbalanced classification. 
My current research focuses on the application and modification on random forests. My next step is to learn more about reinforcement learning and online learning, and further explore the solution of fairness, healthcare, and environmental problems by applying novel methods.

## Data-Efficient Random Forest with Feature Space Sampling



## Maximizing Portfolio Predictability with Machine Learning

We construct the maximally predictable portfolio (MPP) of multiple assets using
machine learning. Solving for the optimal constrained weights in the multi-asset MPP
gives us portfolio strategies with a high monthly coefficient of determination, given the
sample covariance matrix of predicted returns from a machine learning model. Various
models for the covariance matrix are tested. The MPP of industry groups constituents
with estimated returns from the machine learning model Random Forest outperforms the
market index and the linear factor model MPP. Then taking the advantage of the high
predictability of the MPP by timing the allocation between the MPP and the risk-free
asset achieves an even greater level of outperformance. Using out-of-sample measures of
predictability including forecast errors, we show that the predictability of the maximally
predictable portfolio is statistically and economically significant. An economic analysis
of the machine learning MPP finds the outperformance can be traced to its enhanced
predictability.

## Feature Selection by Sparse Forests

Tree ensembles distribute feature importance evenly amongst groups of correlated features. The average feature ranking of
the correlated group is suppressed, which reduces interpretability and complicates feature selection. In this project we present
ControlBurn, a feature selection algorithm that uses a weighted LASSO-based feature selection method to prune unnecessary
features from tree ensembles, just as low-intensity fire reduces overgrown vegetation. Like the linear LASSO, ControlBurn
assigns all the feature importance of a correlated group of features to a single feature. Moreover, the algorithm is efficient and only
requires a single training iteration to run, unlike iterative wrapper-based feature selection methods. We show that ControlBurn
performs substantially better than feature selection methods with comparable computational costs on datasets with correlated
features.



