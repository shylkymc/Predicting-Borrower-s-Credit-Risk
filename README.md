# Predicting Borrower's Credit Risk
I created a model to predict delinquent borrowers. I used a data set which is released from The Lending Club. The Lending Club releases data sets every year about borrowers. You can reach the data sets on this [link](https://www.lendingclub.com/auth/login?login_url=%2Fstatistics%2Fadditional-statistics%3F). I started with data cleaning. I used Pandas for the data cleaning process. I dropped some columns and entries which are useless, and set a binary system for "loan_status" column. After that, I started to prepare features. I detected some missing values. I used diffirent strategies to get rid of these missing values. I dropped some of them. Some of them were changed to numerical type from other types, because I need numerical data for the machine learning process. I used mapping method to encode "emp_lenght". I prepared data by fixing entries. 
In my last step, I came to the prediction stage. I set models with logistic regression and random forest classifier. I evaluated my models success with FPR, TPR and confusion matrix metrics. 

## Conlusion
In this project my aim is predicting most of the unpaid borrowers. On this aim, I planned to reduce FPR value. 

Logistic regression model is more successful than random forest classifier.

I reduced FPR value to 11% with logistic regression model. 

My model predicted 5197 unpaid borrowers from 5389 unpaid borrowers data, truly. 


