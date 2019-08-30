# AV-India-ML
India ML Hiring Hackathon 2019

This is the first time I did the submission for a hackathon.

Approach
Most of the time is spent on data analysis part. I droped few columns from the dataset which I felt are of no use like loan_id", "source", "financial_institution", "origination_date", "first_payment_date","loan_purpose”.  I tried various models like random forest and tried to tune the model with random search. Since the target variable was highly unbalanced, I tried SMOTE to balance the target variable distribution. After random forest with tuned parameters scored the 0.2690058480 in LB. 

How to run the code?
Order of files to run
1.	Random Forest.ipynb - Code file to build the Random Forest model.
