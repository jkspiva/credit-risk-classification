# Credit-Risk-Classification
Module 20 - Supervised Learning


## Background

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


## Instructions

The instructions for this Challenge are divided into the following subsections:
* Split the Data into Training and Testing Sets
* Create a Logistic Regression Model with the Original Data
* Write a Credit Risk Analysis Report

### Split the Data into Training and Testing Sets

Open the starter code notebook and use it to complete the following steps:
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.
#### Note
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

