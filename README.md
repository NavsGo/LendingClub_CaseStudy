# Lending Club Case Study

## Table of Contents

* [Introduction](#introduction)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contacts)


## Introduction

### Background: 
For a lending business house, two types of customer risks may affect their business negatively. Those are
 - Customer defaults:
       When the customers don't pay back the full loan amount due to any reason. This is called credit risk and causes a loss in capital.
 - Opportunity loss: 
       During the loan verification process, the loan application is rejected for an eligible customer wrongly and hence missing the business opportunity. This will impact the potential growth of business and ultimately monetary losses.

### Business Problem: 
 We are to identify the various customer attributes and loan attributes that drive the loan status and can be used to decide in making better decisions about lending loans. Eventually, this will reduce credit losses.
### Dataset:
We have about 40k loan records which contain loan attributes(rate, installment, interest rates etc) and customer financial information for all those loans. All loan applications also have loan status which can be
- Fully Paid: It represents the loan is fully paid back. Ideal closure status
- Charged Off: This represents the customer has defaulted somewhere during loan term. These are the loans causing credit loss.
- Current: this case study is to identify the factors that drive a loan to default. It is based on the 40K loan application records, where personal & financial details of each customer and terms wof loans are provided.
  PS: The data related to rejected loan applications is not provided. Hence, the opportunity losses will be out of scope of this case study.

## Conclusions
1. Total number of loans issued steadily increase over the years. However, percentage of loan defaults increase. More market/customer adjustments to be done to cater to changing market condtitions.
2. The customer default rate is directly related to loan grades. More stringent evaluation for loans falling in lower grade category.
3. Though the loans issued to home owners are much less, the Charged off rate for these loans is still higher than for customers with mortgages. Further analysis suggests for same dti, the home owners customers have higher charge offs even when they have less credit utilization. This indicates there may be some market factors affecting the ability of home owners to pay back. More analysis required to understand the actions to consider how to better decide loans for home owners.
4. The customers with OTHER category has maximum default rate and need closer examination by dividing it in further sub categories.
5. The customers who have taken loan for small businesses are much more likely that other purposes. The evaluation for these loans should be looked at.
6. About 14% of loans defult in total.
7. The loans with larger term duration are more likely to default than lower term loans. 

## Technologies Used

- seaborn 0.11.1
- jupyter 1.0.0
- numpy 1.20.1
- anaconda 2021.05
- python 3.8.8
- matplotlib 3.3.4
- Microsoft excel

## Acknowledgements

[Priyanka](https://github.com/priyanka9199)- This project was done as part of group case study with Priyanka as my team member.

## Contacts

Created by [Navita Goel](https://github.com/NavsGo)- feel free to contact me!
