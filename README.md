# credit-risk-classification

The following in-class activities helped with structuring the code: logistic_regression_solution, random_forest_solution, decision_trees_solution


Overview of the Analysis
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

Explain the purpose of the analysis.
Explain what financial information the data was on, and what you needed to predict.
Provide basic information about the variables you were trying to predict (e.g., value_counts).
Describe the stages of the machine learning process you went through as part of this analysis.
Briefly touch on any methods you used (e.g., LogisticRegression, or any resampling method).
Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1:

Description of Model 1 Accuracy, Precision, and Recall scores.
Machine Learning Model 2:

Description of Model 2 Accuracy, Precision, and Recall scores.
Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Which one seems to perform best? How do you know it performs best?
Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's? )
If you do not recommend any of the models, please justify your reasoning.


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
