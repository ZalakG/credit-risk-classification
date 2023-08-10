# credit-risk-classification (Week-20 Challenge)
----------------------------
An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

# Module 12 Report Template

## Overview of the Analysis

* The purpose of this analysis is to create a model which predict a loan that is less risky(healthy loan which is likely to be paid off fully without any problem) vs. risky loan(high risk loan in which comapany may not receive full payment or the borrower fail to pay entire amount).

* The data inclued Loan_size, Interest_Rate, Borrower_income, debt_to_income, num_of_accounts, derogotory_marks, total_debt and loan_status for 77,536 loans. Based on the data the goal is to create a model which predicts if the loan is healthy(low-risk) or risky(high-risk).

* First load the data from the provided csv file to analyse and understand the dataset.

* Then the data was seperated into 2 datasets for trainning and testing using sklearn module train_test_split.

* After seperating data, linear logistic regression model initiated and training dataset was fitted to the model.

* Then fitted model used to make predictions of testing dataset.

# Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

## Machine Learning Model 1:

* Balanced Accuracy Score
	* 99%

* Precision Score:
	* 100% for Healthy Loans
	* 87% for High Risk Loans

* Recall Score:
	* 100% for healthy loans
	* 89% for High Risk Loans

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any.

* The model seems to be predicting high accuracy(99%) and high precision score for healthy loan(100%) than the high risk loan(87%).

* Overall, this model seems fairly good for the company for healthy loan but at the same time there is 12% to 13% chance that comapany may get loss with the false positive predictions. I would recommend this model for company.


# Project Requirements:
-----------------------

Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.







