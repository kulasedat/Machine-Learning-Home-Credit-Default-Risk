It is really fact that many people are having problems to get loans due to insufficient or non-existent credit histories. Companies like Home Credit try to broaden financial inclusion for these struggled population by providing them a safe borrowing experience. It is for sure that Home Credit makes use of a differente data to predict their clients' repayment abilities.

The aim of this project is to use historical loan application data provided by Home Credit to predict whether an applicant will be able to repay a loan or not. 

This is a standard supervised classification task by using Light GBM.

This project starts with the Data Exploration to learn more what our data can tell us.

Overview of the Dataset

+ application_{train|test}.csv: This is a main table, broken into two files for Train (including TARGET) and Test (without TARGET).
+ bureau.csv: This data provides info about all client's previous credits provided by other financial institutions.
+ bureau_balance.csv: Monthly balances of previous credits in Credit Bureau.
+ POS_CASH_balance.csv: Monthly balance of previous point of sales and cash loans that the applicants had with the Home Credit.
+ credit_card_balance.csv: Monthly balance of previous credit cards that the applicants have with the Home Credit.
+ previous_application.csv: All previous applications of clients for Home Credit loans.
+ installments_payments.csv: Repayment situation of the previously disbursed credits in Home Credit.

Following notebook was used as a reference for this study. 
Reference Notebook => https://www.kaggle.com/jsaguiar/lightgbm-with-simple-features

After implementing the Light GBM, final scores for the full solution were 0.79590 (5 fold), 0.79573 (10 fold)

This study is a result of collaborative group work conducted within VBO Machine Learning Bootcamp
