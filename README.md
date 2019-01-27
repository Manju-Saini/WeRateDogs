# WeRateDogs
Udacity Data Analyst Nanodegree Project - Wrangle and Analyze Data using WeRateDogs data

# Introduction

This project was part of the data wrangling section of the Udacity Data Analyst Nanodegree program and is primarily focused on wrangling data from the WeRateDogs Twitter account using Python, documented in a Jupyter Notebook (wrangle_act.ipynb)

# Project Details

In this project, we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it using Python and its libraries.

The tasks for this project are:

- Data wrangling, which consists of:
  - Gathering data
  - Assessing data
  - Cleaning data
- Storing, analyzing, and visualizing your wrangled data
- Reporting on data wrangling efforts and data analyses and visualizations

# Data

The WeRateDogs Twitter archive was downloaded from a link provided by Udacity.

The file image_predictions.tsv, which contains tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) was hosted on Udacity's servers and was downloaded programmatically using the Requests library.

Each tweet's retweet count and favorite ("like") count was gathered by query to the Twitter API, stored each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON data was written to its own line. Then read this .txt file line by line into a pandas DataFrame with tweet ID, retweet count, and favorite count.
