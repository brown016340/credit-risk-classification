# Module 12 Report Template

## Overview of the Analysis

A dataset of historical lending activity from a peer-to-peer lending services company was used to build a model that could help inform whether an individual is a high risk borrower or not. The data used to train the model contained the following information: loan_size, interest_rate, orrower_income, debt_to_income,num_of_accounts, derogatory_marks, total_debt, loan_status, with the final variable, loan status being what the model is trained to predict. A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

## Results

* The balanced accuracy is 96.8%

* The percision is 1 for healthy loans and .84 for at risk loans

* The recall scores are .99 for healthy loans and .94 for at risk loans

## Summary

This model can predict fairly accuratly however it produces more false negatives than false positves. More false negatives would be slightly more favorable to the loaning entity as it is not falsely giving loans to those individuals with a risky history.
