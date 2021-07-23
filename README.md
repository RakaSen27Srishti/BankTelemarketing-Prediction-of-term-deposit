# BankTelemarketing-Prediction-of-term-deposit
## Collaborators:
1. Atrayee Dutta Chowdhury
2. Purvita Mandal
3. Raka Sen
4. Raktima Dey
## Domain of the project:
 Banking
 ## About the dataset:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
The dataset was picked from UCI Machine Learning Repository.There are four variants of the datasets out of which we chose “ bank-additional-full.csv” which consists of 41188 data points with 20 independent variables out of which 10 are numeric features and 10 are categorical features. Further details about the list of features in the dataset can be found at https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
## Objective:
Predicting whether a customer will subscribe a term deposit or not given customer relationship data.
## Problem statement: 
 Analyse the  prior marketing campaigns of the given Portuguese Bank and predict if the user will buy the Bank’s term deposit or not.
## Type of Machine Learning problem:
This is a binary classification problem. Our two classes are “yes” denoting that the customer subscribed to a term deposit, and “no” denoting that the customer did not subscribe.The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y) using Logistic Regression.
## Language used:
Python
## Explanatory Data Analysis
Exploratory data analysis (EDA) is used to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods. It helps determine how best to manipulate data sources to get the answers we need, making it easier for us to discover patterns, spot anomalies, test a hypothesis, or check assumptions.
Our EDA includes:
1) Calling the necessary libraries and importing the dataset.
2) Describing the data.
3) Data cleaning-Finding missing values,duplicate entries and presence of outliers.
4) Visualization of Univariate data using countplots and histplot.
5) Heatmap depicting correlation coefficient between numerical variables.
6) Study of association between target variable and various categorical variables using chisquare test for independece. Calculated Chi-square measure of contingency and Crammer's V to find strength the of association. 
7) Study of association between target variable and various numerical variables using boxplot .(We did not use Point Biserial Correlation since the data did not satisfy all the assumptions required for its application)
## Meeting 3: Logistic Regression
1) Fit Logistic Regression and Regularized Logistic Regression.
2) Use ROC curve to decide the threshold for decision.
3) Use AUC ROC , precision, recall and F1-score as metrices for classification.
