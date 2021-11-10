# Lending Club Case Study
> This is a largest consumer finance company which specialises in lending various types of loans to urban customers. The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Table of Contents
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)

## General Information
This is a largest consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two **types of risks** are associated with the bank’s decision:

- If the applicant is **likely to repay the loan**, then not approving the loan results in a **loss of business** to the company

- If the applicant is **not likely to repay the loan**, i.e. he/she is likely to default, then approving the loan may lead to a **financial loss** for the company

When a person applies for a loan, there are **two types of decisions** that could be taken by the company:

1. **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:

   1. **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate)

   2. **Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

   3. **Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
   
2. **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who **default** cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the **driving factors** (or **driver variables**) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Conclusions

Following are the few driving factors for loan getting default based on the EDA done:

- Higher Interest Rate (> 15%) - As the interest rate increases the number of loans charged off increases
- Loan Term (60 Months) - As the Loan term increases the number of loans charged off also increases
- Higher Loan Amount( > 30000) - As the loan amount increases there is an increase in loan defaults
- Loan Grade - Loan Grades E,F and G have higher loan defaults
- Annual Income - As the annual income decreases the percentage of loan defaults also increases. This is a negative correlation
- State - Loan applications from NV, AK, TN are defaulted more

## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.2
- matplotlib - version 3.4.2
- seaborn - version 0.11.2

## Contact
Created by Vivek Paradkar - feel free to contact me!
