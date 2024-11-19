# Lending Club Case Study

## Table of Contents

* [Introduction](#introduction)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contacts)


## Introduction

### Background: 
For a consumer finance company, two types of risks are associated with their decision to approve or reject any loan application. Those are
 - Customer defaults:
   If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
 - Opportunity loss: 
       If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

### Business Problem: 
 To reduce the risks associated with the approval process, we are to identify patterns to indicate if a person is likely to default, which may then be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
 
### Dataset:
We have about 40k loan records which contain loan attributes(rate, installment, interest rates etc) and customer financial information for all those loans. All loan applications also have loan status (target variable) which can be
- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
- Current: Applicant is in the process of paying the installments, i.e. the tenure of the loan is not yet completed. These candidates are not labeled as 'defaulted'.
- Charged-off: Applicant has not paid the installments in due time for a long time, i.e. he/she has defaulted on the loan 
PS: The data related to rejected loan applications is not provided. Hence, the opportunity losses will be out of scope for this case study. Also, Current loan records will be ignored as we don't know if they will default or not. Hence can't be studied to find required trends.  

## Conclusions
1. In total, about 14.15% of loans have defaulted.
2. The total number of issued loans steadily increases over the years which indicates a growing business. However, the percentage of loan defaults is increasing. This suggests that the current criteria for loan approval does not adjust to changing market conditions with time.
3. The loan default rate consistently increases with lowering loan grades. More stringent evaluation criteria needed for loans falling in lower grades.
4. The loans with larger term duration are more likely to default than lower term loans.
5. Though the loans issued to home owners are much less, loan Charged off rate for these loans is still higher than for customers with mortgages. Further analysis suggests for same dti, the home owners customers have higher charge offs even when they have less credit utilization. This indicates there may be some customer's personal(age etc) or market factors affecting the ability of home owners to pay back. More analysis is required to understand the actions to consider how to better decide for loans for home owners.
6. The customers with OTHER category has maximum default rate and need closer examination by dividing it in further sub categories.
7. The customers who have taken loan for small businesses are much more likely that other purposes. The evaluation for these loans should be revisited.
## Technologies Used

- seaborn 0.11.1
- jupyter 1.0.0
- numpy 1.20.1
- anaconda 2021.05
- python 3.8.8
- matplotlib 3.3.4
- Microsoft excel

## Acknowledgements

[Priyanka](https://github.com/priyanka9199)- This project was done as part of the group case study with Priyanka as my team member.

## Contacts

Created by [Navita Goel](https://github.com/NavsGo)- feel free to contact me!
