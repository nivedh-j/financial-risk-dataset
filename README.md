# Customer Credit Risk Dataset

## Overview

This dataset contains detailed customer financial and credit behavior data collected for credit risk analysis and payment delinquency prediction. It includes demographic information, credit scores, loan balances, employment status, and detailed payment history over six months. This dataset can be used to build models for credit scoring, risk assessment, and customer financial profiling.

## Dataset Description

| Column Name           | Description                                                         |
|----------------------|---------------------------------------------------------------------|
| Customer_ID          | Unique identifier for each customer                                 |
| Age                  | Age of the customer                                                 |
| Income               | Annual income of the customer                                       |
| Credit_Score         | Credit score value                                                  |
| Credit_Utilization   | Ratio of used credit to total credit limit                         |
| Missed_Payments      | Number of missed payments                                          |
| Delinquent_Account   | Indicator if the account is delinquent (1 = yes, 0 = no)           |
| Loan_Balance         | Outstanding loan balance                                           |
| Debt_to_Income_Ratio | Ratio of debt payments to income                                   |
| Employment_Status    | Employment status (e.g., EMP, Self-employed, Unemployed)            |
| Account_Tenure       | Duration of account in months                                      |
| Credit_Card_Type     | Type of credit card (Standard, Platinum, Student, etc.)           |
| Location             | Geographic location of the customer                                |
| Month_1 to Month_6   | Payment status for the last six months (On-time, Late, Missed)     |

## Sample Data

| Customer_ID | Age | Income | Credit_Score | Credit_Utilization | Missed_Payments | Delinquent_Account | Loan_Balance | Debt_to_Income_Ratio | Employment_Status | Account_Tenure | Credit_Card_Type | Location     | Month_1 | Month_2 | Month_3 | Month_4 | Month_5 | Month_6 |
|-------------|-----|--------|--------------|--------------------|-----------------|--------------------|--------------|---------------------|-------------------|----------------|------------------|--------------|---------|---------|---------|---------|---------|---------|
| CUST0001    | 56  | 165580 | 398          | 0.3905             | 3               | 0                  | 16310        | 0.3174              | EMP               | 18             | Student          | Los Angeles  | Late    | Late    | Missed  | Late    | Missed  | Late    |
| CUST0002    | 69  | 100999 | 493          | 0.3124             | 6               | 1                  | 17401        | 0.1961              | Self-employed     | 0              | Standard         | Phoenix      | Missed  | Missed  | Late    | Missed  | On-time | On-time |

## Usage

- This dataset is ideal for building predictive models related to:
  - Credit risk and delinquency prediction
  - Financial behavior analytics
  - Customer segmentation based on credit usage and payment patterns

## License

This dataset is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


---

Feel free to ask if you want me to add sections like Installation, How to Contribute, or anything else!
