# Data Dictionary

| Column | Type | Description |
|---|---|---|
| Month | Categorical | Calendar month of the record (January-August) for the customer. |
| Age | Numeric | Customer age in years. Cleaned to a realistic range of 18-100. |
| Occupation | Categorical | Customer's stated occupation. Missing placeholder values imputed with the mode. |
| Annual_Income | Numeric | Customer's reported annual income in dollars. Outliers beyond the 1st-99th percentile treated as missing. |
| Monthly_Inhand_Salary | Numeric | Customer's monthly take-home salary in dollars. |
| Num_Bank_Accounts | Numeric | Number of bank accounts held. Capped to a realistic range of 0-11. |
| Num_Credit_Card | Numeric | Number of credit cards held. Capped to a realistic range of 0-11. |
| Interest_Rate | Numeric | Average interest rate (%) across the customer's credit accounts. Capped to 1-34. |
| Num_of_Loan | Numeric | Number of loans currently held. Capped to 0-9. |
| Type_of_Loan | Categorical | Comma-separated list of loan types held by the customer. |
| Delay_from_due_date | Numeric | Average number of days payments are delayed past the due date. |
| Num_of_Delayed_Payment | Numeric | Number of delayed payments. Capped to a realistic range of 0-28. |
| Changed_Credit_Limit | Numeric | Percentage change in the customer's credit limit. |
| Num_Credit_Inquiries | Numeric | Number of credit inquiries made. Capped to a realistic range of 0-17. |
| Credit_Mix | Categorical | Classification of the customer's mix of credit types (Good, Standard, Bad). |
| Outstanding_Debt | Numeric | Remaining outstanding debt in dollars. |
| Credit_Utilization_Ratio | Numeric | Percentage of available credit currently being used. |
| Payment_of_Min_Amount | Categorical | Whether the customer pays only the minimum amount due (Yes/No). |
| Total_EMI_per_month | Numeric | Total monthly equated installment payments across all loans, in dollars. |
| Amount_invested_monthly | Numeric | Amount the customer invests monthly, in dollars. |
| Payment_Behaviour | Categorical | Descriptive label of the customer's spending and payment pattern. |
| Monthly_Balance | Numeric | Customer's average monthly account balance in dollars. |
| Credit_Score | Categorical | Target variable: credit score category (Poor, Standard, Good). |
| Credit_History_Age_Months | Numeric | Total length of the customer's credit history, converted from text to total months. |

# Descriptive Statistics

| Variable | Mean | Median | Std Dev | Min | Max |
|---|---|---|---|---|---|
| Age | 34.43 | 34.00 | 10.12 | 18.00 | 100.00 |
| Annual_Income | 51,443.42 | 38,073.60 | 38,347.26 | 7,567.51 | 267,236.00 |
| Monthly_Inhand_Salary | 4,088.17 | 3,133.33 | 2,994.99 | 303.65 | 15,204.63 |
| Num_Bank_Accounts | 5.28 | 5.00 | 2.58 | 0.00 | 11.00 |
| Num_Credit_Card | 5.47 | 5.00 | 2.03 | 0.00 | 11.00 |
| Interest_Rate | 14.15 | 12.00 | 8.58 | 1.00 | 34.00 |
| Num_of_Loan | 3.42 | 3.00 | 2.38 | 0.00 | 9.00 |
| Delay_from_due_date | 20.60 | 17.00 | 14.68 | -5.00 | 67.00 |
| Num_of_Delayed_Payment | 13.19 | 13.00 | 5.95 | 0.00 | 28.00 |
| Changed_Credit_Limit | 10.18 | 9.23 | 6.68 | -6.48 | 36.97 |
| Num_Credit_Inquiries | 5.58 | 5.00 | 3.77 | 0.00 | 17.00 |
| Outstanding_Debt | 1,386.62 | 1,124.37 | 1,141.57 | 0.23 | 4,998.07 |
| Credit_Utilization_Ratio | 32.31 | 32.34 | 5.13 | 20.00 | 50.00 |
| Total_EMI_per_month | 704.73 | 67.41 | 4,667.56 | 0.00 | 55,771.00 |
| Amount_invested_monthly | 618.91 | 137.41 | 2,002.87 | 0.00 | 10,000.00 |
| Monthly_Balance | 406.67 | 340.26 | 215.49 | 0.01 | 1,602.04 |
| Credit_History_Age_Months | 222.40 | 213.00 | 95.37 | 1.00 | 404.00 |
