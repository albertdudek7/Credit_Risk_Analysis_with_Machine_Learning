# credit-risk-classification

Overview of the Analysis
1. Purpose of Analysis
- The purpose of this analysis was to build a model that will help predict and identify the credit risk classification of a loan from peer-to-peer lending services.
  
2. Loan Classifications
- The two classifications for loans were either healthy(0) or high-risk loans(1).
  
3. Financial Information provided
- The following financial information was provided to aid in the predictions: loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt and loan status. 
- The financial information factored into assessing whether a loan is healthy or a high-risk loan based on those factors. Simply, the probability that the loan would be paid in full and on-time. In other words, the creditworthiness of borrowers.
- The vraibles that I was trying to predict (value_counts) was whether a loan is healthy(0) or a high-risk loan(1). 


4. Describe the stages of the machine learning process you went through as part of this analysis.
   
  The stages of the machine learning process were split into:

  (1) Read the csv data into a Pandas DataFrame.

  (2) Create lavels sets y (loan_status) and create features X DataFrame from the remaining columns. 
  
  (3) Split the data into training and testing sets using train_test_split.
  
  (4) Fit a logistic regression model by using the training data and save predictions for the testing data labels and the fitted model.
  
  (5) Test and Evaluate the model's performance by generating a confusion matrix and printing the classification report. 

5. Briefly touch on any methods you used (e.g., LogisticRegression, or any resampling method).
- A logistic regression model was fit using the training data. The predictions for the testing data lavels were saved by using the testing feature data and the fitted model.

Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1:

Description of Model 1 Accuracy, Precision, and Recall scores.





The following in-class activities helped with structuring the code: logistic_regression_solution, random_forest_solution, decision_trees_solution

Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

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
