# Evaluation of the borrower's creditworthiness

## Task

The customer is the credit department of the bank. It is necessary to understand whether the marital status and the number of children of the client affect the repayment of the loan on time. The statistics on the solvency of customers is used as an input data.
The research results will be taken into account when building a model of ** credit scoring** — a special system that evaluates the ability of a potential borrower to repay a loan to the bank.

**Data description:**

- children — the number of children in the family
- days_employed — total work experience in days
- dob_years — client's age in years
- education — client's education level
- education_id — education level identifier
- family_status — marital status
- family_status_id — id of marital status
- gender — gender of the client
- income_type — type of employment
- debt — whether there was a debt on repayment of loans
- total_income — monthly income
- purpose — the purpose of obtaining a loan

## Libraries

- pandas
- matplotlib
- pymystem3
- functools
- string
- nltk.corpus

## Project description

Based on the data of the bank's credit department, the influence of marital status and the number of children on the fact of repayment of the loan on time was investigated. Information about the data was received. Gaps have been identified and processed. Data types have been replaced with those corresponding to the stored data. Duplicates have been removed and data has been categorized. One dataframe is decomposed into three.

## Keywords

Data processing, duplicates, missed values, categorization, decomposition.
