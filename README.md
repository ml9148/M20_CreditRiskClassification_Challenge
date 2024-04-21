# M20_CreditRiskClassification_Challenge
Module 20 - Credit Risk Classification Challenge

## Overview:
The purpose of this analysis is to identify the cred¬¬it worthiness of borrowers, using a list o¬f containing a total of 75,536 loans. The list included the following:
    •	Loan Size
    •	Interest Rate
    •	Borrower Income
    •	Debt To Income
    •	Num Of Accounts
    •	Derogatory Marks
    •	Total Debt
    •	Loan Status

Based on the list and the attributes provided we can review the observe the following:

    •	Total Applications: 		count	$77,536
    •	Average Amount Requested: 	mean	$9,805
    •	Minimum Amount Requested: 	min	    $5,000
    •	Maximum Amount Requested: 	max	    $23,800
    •	Loan Status (0=Healthy Loan, 1=Risky Loan): 
        o	75,036 Healthy
        o	2,500 Risky

## Analysis Results:
### Accuracy: 
The analysis has provided a 99.25% accuracy.

### Precision: 
Precision for “Healthy Loans” is 100% and for “Risky Loans” is 84%, this means there are changes that the model can create False Negative, on the “Risky Loans”. And our Confusion Matrix showed that we had 582 of them.

### Recall Scores:
The recall for “Healthy Loans” is 99% effective, making me believe is a good module god standing loans and 94% for “Risky Loans”, this can potentially create false negatives, this supports the results from the Precision Number for the “Risky Loans”.


## Summary:
The Logistic Regression model performed good as it detected “Healthy Loans” with 100% precision; But for the “Risky Loans” it provided 84% of precision, these are 582 False Negatives marked them as risky when they are not. This provides a feel good results for the company but not so much for the customers that were marked down negatively with the model as it is overly cautious.
