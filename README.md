# Credit-Risk-Classification
Module 20 - Supervised Learning


## Background
In this Challenge, we used various techniques to train and evaluate a model based on loan risk. We used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


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


### Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
  - Generate a confusion matrix.
  - Print the classification report.
4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Credit Risk Analysis Report (see below)
A brief report that includes a summary and analysis of the performance of the machine learning models that were used was written below.

Overview of the Analysis: The purpose of this analysis was to train and evaluate our logistic regression model to see how well it can predict a healthy or unhealthy, high-risk loan label.


The Results:
* According to the classfication report the accuracy score of our logistic regression model was 99%. The accuracy score tells us that our model is correct 99% of the time.
* The precision scores of 1.00 for healthy loans (0) tells us that our 100% of the predicted positives were correct. The precision score of 85% for unhealthy, high-risk loans (1) tells us that our model predicted 85% of the unhealthy loans correctly. The macro average of the precision score was 92%. Our model's overall precision score was 92%.
* The recall scores of 99% (0) and 91% (1), with a macro average of 95% tells us that our model was 95% accurate is measuring all true positives.

In summary, although our model has 92% precision score and a 95% recall score, I would have more confidence in utilizing a model that scores at least 95% in all areas. Although our model is great at predicting and identifying healthy loans and relatively well at identifying unhealthy loans, I would not recommend the use of our model by the company. 
