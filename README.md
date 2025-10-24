# Customer Credit Risk Dataset

## Overview

This dataset contains detailed customer financial and credit behavior data collected for credit risk analysis and payment delinquency prediction. It includes demographic information, credit scores, loan balances, employment status, and detailed payment history over six months. This dataset can be used to build models for credit scoring, risk assessment, and customer financial profiling.

## Dataset Description

| Field               | Description                                     |
|---------------------|------------------------------------------------|
| Customer_ID         | Unique identifier for each customer             |
| Age                 | Customer age in years                            |
| Income              | Annual income in USD                             |
| Credit_Score        | Credit score (lower means higher risk)          |
| Credit_Utilization  | Ratio of credit used to total credit available  | 
| Missed_Payments     | Number of missed payments                        |
| Delinquent_Account  | Whether the account has delinquent status (0/1)|
| Loan_Balance        | Outstanding loan balance in USD                  |
| Debt_to_Income_Ratio| Ratio of debt payments to income                 |
| Employment_Status   | Employment status (EMP, Self-employed, Unemployed) |
| Account_Tenure      | Number of years with the credit account          |
| Credit_Card_Type    | Type of credit card held (Standard, Platinum, Student) |
| Location            | Customer location (city)                          |
| Month_1 to Month_6  | Payment status for last 6 months (On-time, Late, Missed) |

## Sample Data

| Customer_ID | Age | Income | Credit_Score | Credit_Utilization | Missed_Payments | Delinquent_Account | Loan_Balance | Debt_to_Income_Ratio | Employment_Status | Account_Tenure | Credit_Card_Type | Location    | Month_1 | Month_2 | Month_3 | Month_4 | Month_5 | Month_6 |
|-------------|-----|--------|--------------|--------------------|-----------------|--------------------|--------------|---------------------|-------------------|----------------|------------------|-------------|---------|---------|---------|---------|---------|---------|
| CUST0001    | 56  | 165580 | 398          | 0.3905             | 2               | 0                  | 16310        | 0.3174              | EMP               | 18             | Student          | Los Angeles | Late    | Late    | Missed  | Late    | Missed  | Late    |
| CUST0002    | 69  | 100999 | 493          | 0.3124             | 3               | 1                  | 17401        | 0.1961              | Self-employed     | 0              | Standard         | Phoenix     | Missed  | Missed  | Late    | Missed  | On-time | On-time |
| CUST0003    | 46  | 188416 | 500          | 0.3599             | 2               | 0                  | 13761        | 0.3017              | Self-employed     | 1              | Platinum         | Chicago     | Missed  | Late    | Late    | On-time | Missed  | Late    |

## Usage

- This dataset is ideal for building predictive models related to:
  - Credit risk and delinquency prediction
  - Financial behavior analytics
  - Customer segmentation based on credit usage and payment patterns

## License

This dataset is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


---

Feel free to ask if you want me to add sections like Installation, How to Contribute, or anything else!
