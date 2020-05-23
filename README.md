
# Capstone Project: Create a Customer Segmentation Report for Arvato Financial Services
Udacity Data Scientist Nanodegree capstone project to create Customer Segmentation for Arvato Financial Services
You can read my Medium Blog Post in [here](https://medium.com/@pradeepan.prabha/customer-segmentation-report-arvato-financial-solutions-6fb8e4466dc9).

## Project Motivation

The goal of this project is to predict which individuals are most likely to convert into becoming customers for a mail-order sales company in Germany.

### Installations

This project requires **Python 3.x** and the following Python libraries installed:

- conda install xgboost
- seaborn
- scikit
- plotly
- pandas
- numpy
- matplotlib

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.


## 1. Project Overview

In this project, we are provided with demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany. Using this data, we are required to identify new customers for the company.

We approach this project in 2 phases:
* Use Unsupervised Learning to perform customer segmentation and identify clusters/segments from general population who best match mail-order company's customer base.
* Use Supervised Learning to identify targets for marketing campaign of the mail-order company who could possibly become their customers.

Goal of this project is to predict individuals who are most likely to become customers for a mail-order sales company in Germany.


## 2. Technical overview:

Step by step workflow from data exploration, processing to inference is approached in a structured fashion. Because of the large volume of source data, we build preprocessing pipeline  to get rid of unnecessary and outlier data and implement Dimensionality Reduction and Clustering to identify segments. Due to the nature of the data (details in notebook), AUC/ROC is used as the evaluation metric for this project. Prediction for test set is to be submitted to Kaggle competition for evaluation.

Following concepts implemented and covered in detail in the notebook: 
* Data Exploration & Cleansing
* Dimensionality Reduction
* Clustering
* Supervised Learning
* Final Model Evaluation
* Feature Importance
* Analysis of identified important features in clusters to find relevance
* Scoring and submisstion to Kaggle