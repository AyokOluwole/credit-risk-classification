# credit-risk-classification


Overview: 

•   The objective is to develop a model capable of assessing the creditworthiness of borrowers. The "loan status" column serves as a key indicator, where a value of 0 signifies a healthy loan, while a value of 1 indicates a higher risk of default. This analysis focuses on predicting loan default based on factors such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status.
•   Initially, the loan status was separated to define the x and y values in our data frame accurately. Subsequently, a logistic regression model was applied using the training data (X_train and y_train) to fit the original dataset. The model's performance was then evaluated using metrics such as balanced accuracy, confusion matrix, and classification report, including precision, recall, f1-score, and support.
•   Furthermore, a Logistic Regression classifier was employed using resampled data to train the model, make predictions, and evaluate its performance.

Definitions:
•   Precision: Precision measures the model's ability to accurately predict. With the first model being healthy loans were 1.00 and High-risk loans were 0.85. That is 100% on healthy loans and 85% on High-risk loans. While model 2 was 1.00 and 0.84. That is 100% on healthy loans and 84% on High-risk loans.
•   Recall: The recall metric assesses how well the model can identify positive samples. In the first model healthy loans were 0.99 and High-risk loans were 0.91. That is 99% on healthy loans and 91% on High-risk loans. While model 2 was 0.99 and 0.99. That is 99% on healthy loans and 99% on High-risk loans. 
•   Balanced accuracy:  In the first model, The Balanced Accuracy score of the model is: 0.9520479254722232 that is model was 95% accurate.  In the second model, The Balanced Accuracy score of the model is: 0.9936781215845847 that is model was 99% accurate. 

Recommendation: 
•    In taking a look at both models, it is best and safe to go with model 2 as it had an accuracy of 99%. 
