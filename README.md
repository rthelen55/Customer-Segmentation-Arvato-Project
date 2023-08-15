
# Capstone Project: Arvato Financial Services
Udacity Data Scientist Nanodegree capstone project to create Customer Segmentation for Arvato Financial Services

BLOG: https://medium.com/@rkmradiokilledmusic/496109424917?postPublishedType=initial

## Table of Contents

- [Project Overview](#projectoverview)
- [Technical Summary](#technicalsummary)
- [Requirements](#requirements)

***

<a id='projectoverview'></a>

## 1. Project Overview

In this project, we are tasked with using the Arvato financial services data to evaluate which customer's should be targeted in marketing campaigns. 

We use two different methods to determine which demographic group of people are most likely to be converted to customers
* Use Unsupervised Learning to perform customer segmentation and identify clusters from general population and compare that to the clusters of the current customer base. This allows us to determine which customers demographics are most likely to be converted
* Use Supervised Learning to identify which people are most likely to be converted into customer's following marketing campaigns

The goal of the project was to identify customer's that would most likely be converted into a customer of a mail service company in Germany


<a id='technicalsummary'></a>

## 2. Technical summary:

This project covers all the steps for unsupervised and supervised learning techniques. Unsupervised learning is a type of machine learning where the model is not provided with any labeled data. Instead, it must find patterns and relationships in the data on its own. Supervised learning, on the other hand, is a type of machine learning where the model is provided with labeled data and must learn to make predictions based on that data.

In order to prepare the data for these techniques, we will implement data cleansing, data processing, dimensionality reduction, clustering, and segmentation. Data cleansing involves identifying and correcting errors in the dataset, such as dealing with missing or inconsistent data, removing duplicates, and handling outliers. These steps include data transformation, feature selection, normalization, and reduction. The goal of data processing is to convert raw data into a suitable format that machine learning algorithms can learn.

Dimensionality reduction is the process of reducing the number of features in the dataset while retaining as much information as possible. This can be done using techniques such as Principal Component Analysis.

Clustering is the process of grouping similar data points together based on their characteristics. This will be done using K-means clustering technique. 

Segmentation is the process of dividing the dataset into smaller groups based on specific criteria. This can be done using techniques such as decision trees or random forests.

Following data concepts are implemented and covered in detail in the jupyter notebook: 

* Data Exploration & Cleansing
* Dimensionality Reduction
* Clustering
* Feature Analysis and Weights
* Supervised Learning
* Final Model Evaluation / Hyperparameter tuning

## 3. Requirements

The requirements are captured in requirements.txt. 
Run: pip install -r requirements.txt



