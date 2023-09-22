# Credit Risk Analysis with Logistic Regression Model

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
  
![image](https://github.com/albertdudek7/Credit_Risk_Analysis_with_Machine_Learning/assets/127783844/abc26330-90f6-4e7f-b4f9-4f6c314502e7)


  (2) Create lavels sets y (loan_status) and create features X DataFrame from the remaining columns. 
  
  (3) Split the data into training and testing sets using train_test_split.

![image](https://github.com/albertdudek7/Credit_Risk_Analysis_with_Machine_Learning/assets/127783844/0dfe0121-fd62-4b67-8cd1-0bfe9a55a7c5)

  
  (4) Fit a logistic regression model by using the training data and save predictions for the testing data labels and the fitted model.

 ![image](https://github.com/albertdudek7/Credit_Risk_Analysis_with_Machine_Learning/assets/127783844/b7daab4b-046f-4dd1-8d0f-8df18c8fed57)

  
  (5) Test and Evaluate the model's performance by generating a confusion matrix and printing the classification report. 

![image](https://github.com/albertdudek7/Credit_Risk_Analysis_with_Machine_Learning/assets/127783844/355a785d-576f-4efe-a22e-7fd383c31531)


5. Briefly touch on any methods you used (e.g., LogisticRegression, or any resampling method).
- A logistic regression model was fit using the training data. The predictions for the testing data lavels were saved by using the testing feature data and the fitted model.

Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

- The balanced accuracy score was 95.2%. Balanced accuracy score is the arithmetic mean of sensitivity and specificity. Balanced accuracy score evaluates the performance of classification in the presence of imbalanced data. It takes into account both recall and true negative rate. The prediction of balanced accuracy was 95.2% accurate.
- The precision score was 92%. It measures the proportion of positively predicted labels that are accurately correct. Precision score is also known as the positive predictive value.
- The recall score was 95%. Recall is the ability to classify all of the positive samples. It quantifies the number of positive class preidctions made out of all positive examples in the dataset. 

Machine Learning Model 1:

Summary:
- I would recommend the use of this model to predict the creditworthiness of borrowers due to the high accuracy score of 95%. It is a reliable score to predict the repayment of the intial loan. The financial data provided was sufficient and the accuracy score can be used by lenders in their business risk profile to gain profit and maintain a healthy business model. 



NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

