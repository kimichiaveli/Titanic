# TITANIC
Data Science Project 101. This is my work on the most popular [dataset](https://www.kaggle.com/c/titanic) for aspiring Data Scientist.

## Overview

The dataset is split into two sets, training and test dataset. The goal is to find out how well our model performs on unseen data (test dataset) and based on previous result we try to build another but better model. The predictions are based on the "features" like passengers, cabin code, age, tickets, etc.

## Approach

This repo consists of many notebooks with different approach on how to predict the test dataset:

1. titanic_xgblr (null cabin mapped as 'missing', null fare dropped, null embarked dropped, null age predicted with linear regression, model built with gridsearchcv xgboost)

## Future Works

1. Feature engineering on passenger information (does honorific from passenger's name have any effect on survivability?)
2. Using catboost algorithm

