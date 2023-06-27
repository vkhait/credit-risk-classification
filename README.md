# credit-risk-classification

The purpose of the analysis was to compare two machine learning models, seeing if it can predict healthy loans more accurately than high risk loans.

The dataset consisted of the following columns: 
loan_size    interest_rate    borrower_income    debt_to_income    num_of_accounts    derogatory_marks    total_debt    loan_status

I used the loan_status as the category to attempt the prediction, whilst the rest of the columns were used to train the data and form the predictions.

## To prepare the data:

I separated data into features and labels, used the 'train test split' function to split the features and labels into testing and training datasets. 

I then imported the machine learning model, instantiate the model, fit the model using the training data, used the model to make predictions. Finally, used the model to evaluate the predictions.

For the second model, I went trrough the same steps but with the sampled dataset.

Methods used:

LogisticRedgression, Train Test Split, Confusion Matrix, Classification Report.

## Results:

* Machine Learning Model 1:
  * Accuracy score:  99%,
  * Precision score: Class 0: 1.00, Class 1: 0.87 , 
  * Recall score: Class 0: 1.00, Class 1: 0.89
  
* Machine Learning Model 2:
  * Accuracy score:  100%,
  * Precision score: Class 0: 1.00, Class 1: 0.87 , 
  * Recall score: Class 0: 1.00, Class 1: 1.00
  
  
## Summary:
  
 Healthy loans in both models were predicted perfectly, high risk loans at 87%, which is not as good. This means that Class 1 (high risk loans) is more likely to give false positives than the false negatives. The logistic regression model (model 1), given the features that were used to train the model, did a good job at predicting the loans. 
 
 Model 2 performed slightly better on average, but the difference between the models wasn't drastic. Both models are good to use.
 
 If the purpose of the model is to predict high risk loans, then both models produced the same results at 87%, which is not perfect. It would be helpful to test the models against more datasets to confirm the results.
 
 
 
 
     
  

