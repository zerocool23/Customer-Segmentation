# Customer-Segmentation by Clustering
### Introduction

Machine learning comes in handy for this task. Particularly, clustering, the most important unsupervised learning problem, is able to create categories grouping similar individuals.  
  
These categories are called clusters. A cluster is a collection of points in a dataset. These points are more similar between them than they are to points belonging to other clusters. Distance-based clustering groups the points into some number of clusters such that distances within the cluster should be small while distances between clusters should be large.  
  
  ## Purpose

The goal of this project is to:
  
1) Perform an exploratory analysis on the dataset.
2) Check that the assumptions K-means makes are fulfilled.
3) Apply K-means clustering algorithm in order to segment customers.

## Data Set Information

The csv file corresponding used herein was downloaded from [Kaggle repository](https://www.kaggle.com/akram24/mall-customers).
The dataset contains data about customers from a Mall. The information gather is: `Customer ID`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`.

## Analysis

This repository contains two files:

- `customer_segmentation.ipybn`: In this jupyter notebook, exploratory data analysis is performed. Moreover, the algorithm assumptions are checked. K-means is applied to segment customers obtaining a graph and the customer segments. It is also shown how to predict to which segment a new customers belongs to. 
- `mall_customers.csv` dataset used to perform the analysis.

The whole analysis was done using Colab and Python, using libraries such as: pandas, numpy, matplotlib, and scikit-learn.

![]()

