# Movie Recommender

## Overview

This repository contains a Python implementation of a Movie Recommender using machine learning techniques.

## Dataset

The MovieLens 20M Dataset is used for training and evaluating the recommender system. You can find the dataset [here](https://grouplens.org/datasets/movielens/20m/). Please download and extract the dataset before running the code.

## Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn
- scipy
- surprise

## Pipeline
```mermaid
graph LR;
  A[Load Dataset] --> B[Content Filtering]
  B --> C[Collaborative Filtering]
  C --> D[Hybrid Recommendation System]
  D --> E[Surprise Library]
```

## Accuracy
The recommender system achieves an accuracy of 91.12%