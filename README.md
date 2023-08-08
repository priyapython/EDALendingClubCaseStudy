# EDA Case study - Lending Club Case study
This case study is to give an idea of applying concepts of EDA in a real business scenario. This case study helps to use the EDA concepts and develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.



## Table of Contents
* Introduction
* Business understanding
* Business objectives
* Approach 



## Introduction
Concepts learnt in python for Data science and Data visualization in Python are used to solve the problem statement with Python 3.0. EDA concepts are implemented in the case study which includes Data Sourcing, Data cleaning, Univariate, Bivariate, segmented univariate analysis.


## Business understanding
Lending  club is  a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.


## Business objectives
Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
 The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment. 

## Approach
1. Necessary libraries imported
2. Data sourcing is executed to read the data from the loan dataset
3. Data understanding and cleaning performed to understand more about the data and removing unnnecessary columns from the dataset
4. Target variable column is the loan_status that helps to identify defaulters
5. Unique columns with single values are identified and removed as it doenst impact the loan_status
6. Column of object type are analysed to convert into required data type for data analysis
7. As the current loan status cannot help in identifying the defaulters , its filtered
8. After the data is cleaned upto required expectation univariate, bivariate, segmented univariate are performed with the target variable loan_status
9. Attributes that impacts are the following 'loan_amnt', 'term', 'int_rate', 'grade', 'sub_grade','emp_length', 'annual_inc','verification_status', 'purpose', 'dti'


## Contact
Created by [@priyapython] - feel free to contact me!
