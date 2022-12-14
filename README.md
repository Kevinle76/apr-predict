
# Credit_Card_Approval_Project

![image](https://user-images.githubusercontent.com/99145651/187097847-df645dc0-bca6-4fb0-86ca-00bdfdfc158c.png)

Credit Card Approvals 

Credit card debt has recently surged in the United States as Americans borrowed billions of dollars to continue spending in the face of growing inflation. Credit card balances increased $46 billion in the second quarter, a 5.5 percent increase from the first quarter, and there was also an uptick in new credit card accounts. The 13 percent increase from the second quarter of 2021 to the second quarter of 2022 was the biggest such jump in more than 20 years. Americans are borrowing more which primarily can be attributable to higher prices. In this project, our goal was to build a credit card approval predictor.

![image](https://user-images.githubusercontent.com/99145651/187246959-508cbd8d-009a-4db8-b8e7-6fc68c7f83ae.png)

 In this project, The APR Group will utilize a datset to determine Credit Card Approval thruogh Machine Learning. The structure will be as follows —

## Tasks
* Loading and viewing the dataset.
* To manipulate data, if there are any missing entries in the dataset.
* To perform exploratory data analysis on dataset.
* To pre-process data before applying machine learning model to the dataset.
* To apply machine learning model that can predict whether an applicant approval for a credit card will be accepted or not.
* Deploy a web application to Heroku

## Importing Libraries
Importing necessary libraries such as NumPy for linear algebra, pandas for data processing, seaborn, and matplotlib for data visualizations.

import pandas as pd
import psycopg2
from sqlalchemy import create_engine

%matplotlib inline

import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score, confusion_matrix
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier

from sklearn import svm
from sklearn.ensemble import RandomForestClassifier
from imblearn.over_sampling import SMOTE

import pickle

## Loading Dataset
.


## Checking and Cleaning of Dataset

Observation: 



# Cleaning data

Removing extraneous columns

Null values

Duplicates


## Data Visualization
For gathering insights.

Classification Modeling

Here, the models used are:-

Random Forest Classifier
Decision Tree Classifier


## Export the model: 

## Develop web application with Flask and intergrate model in the app

## Deployment web app in Heroku




