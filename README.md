# Lending Club Exploratory Data Analysis


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> We have to conduct an exploratory data analysis on a dataset containing loan data from Lending Club. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. We need to isloate the driving factors behind the default i.e. variables that are strong indicators of default.


## Conclusions

### Top variables which are predictors of default:
- Loan term
- Grade of loan
- Number of delinquencies
- Number of open accounts
- Number of public record bankruptcies
- Annual income
- Debt-to-income ratio


### Recommendations (use ROI based approval system)
- The company should be especially careful about its longer term loans.
- Loans with Grade E onwards are risky an should be reduced. 
- The more someone has been delinquent in past 2 years, more are they likely to default; especially 7 and above.
- The more inquiries in last 6 months, more are they likely to default; especially 7 and above.
- Higher number of open accounts suggest more risk. Anyone above 30 open accounts is very risky.
- More derogatory or bankruptcy public records show more riskiness.
- Very high loan amounts are risky along with lower annual income and high debt-to-income ratio.

These recommendations need to be weighed against business profits and an ROI based system should be created to approve loans. The above qualified risk factors should be combined with one another and the probability of default should be calculated (same as the default rate by segments). 

Using this probability of default, the return on investment of every loan judged and some criteria used for approval. We would recommned using an ROI cut-off of 3 to approve loans i.e. approve loans with ROI >= 3.


## Technologies Used
- Python 3
- Jupyter Notebook


## Acknowledgements
Give credit here.
- This project was assigned in EPGP ML AI Programme done by UpGrad in collaboration with IITB
- I thanks all the professors, course contributors, and everyone else involved in the offering of this programme.


## Contact
Created by [@knd08] - feel free to contact me!

