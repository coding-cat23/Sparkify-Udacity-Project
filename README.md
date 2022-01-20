# Sparkify-Udacity-Project

## Introduction
This project has been completed as part of the Udacity Datascientist Nanodegree.

Sparkify is a music streaming service that has been made up for this project. Similar to well known digital streaming services, our made-up users can have a free or paid account. They can also cancel their membership at any time.

The dataset used for this project is a collection of page events, for example when a user listened to a song, liked a song, or cancelled their membership.

To grow revenue streams, Sparkify would like to identify users that might potentially cancel, based on historic data of other users that cancelled. This is the objective of our project - to predict user churn based on the page events.

## Installation
Since I used the Udacity workspace to complete this project, these are the requirements to run this project on your local machine:
- Jupyter Notebooks, Python and PySpark API
- Apache Spark 

## Libraries
This project will execute in a Jupyter notebook environment: https://jupyter.org/

It uses pandas library: https://pandas.pydata.org/

It uses PySpark: https://spark.apache.org/docs/latest/api/python/index.html

It makes use of the following sklearn libraries: 
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_curve.html

It makes use of numpy:
https://numpy.org/

It makes us of matplotlib for visuals:
https://matplotlib.org/

It makes use of pyspark.sql:
https://spark.apache.org/docs/2.4.0/api/python/pyspark.sql.html

It also makes use of Pyspark Machine Learning models:
https://spark.apache.org/docs/latest/ml-guide.html


## Project Files
The files contained in this repository:
- Sparkify.ipynb : Jupyter notebook with analysis on the subset of data provided by Udacity
- Sparkify.ipynb :html file that contains the analysis
- mini_sparkify_event_data.json.zip : dataset for this analysis

## Project Overview
This project consists of 4 main sections:
### Loading & Cleaning the dataset
In this section, subset of data is loaded into a Spark dataframe. We get to know the structure, check for duplicates, replace null values, check for missing values and drop unneeded columns
### Exploratory Data Analysis
In this section, our cleaned data is further explored, analysed and visualised, so we can gain an understanding of how to structure features for the machine learning dataset
### Feature Engineering
We use the dataset to construct a new dataframe, with a set of features for each unique user, including whether they churned or not
### Modeling
In the final section, we build, train and test some models and compare their performace on predicting user churn.

## Licensing
The dataset and project is provided by Udacity https://www.udacity.com/
