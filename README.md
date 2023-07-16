# EDA on Lending Club Loan data

Lending Club is a Consumer Finance company for who is interested to understand if a new loan application can be accepted or rejected.
We have a dataset with loan data that are currently active, paid off or charged-off.
We are advising the company with driver variables to avoid credit loss using EDA.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

- We have done univariate and bivariate analysis on the dataset. We have derived metrics which is required.
- We have made assumptions based on publicly available domain information.
- As data imputations can’t be reliably done, this step is skipped and the columns with empty values are dropped from analysis.
- We have also not considered the loan data for the currently active loans as we can’t predict drivers from this.
- Also, we have dropped customer behavior variables as this will be unique and can’t be used to generalize/ aggregate the data.

## Conclusions

- 14% of the loans are defaulted
- Loans were requested mostly for Debt Consolidation and Credit Card
- Median annual income is 60000 USD
- Most of the loans get funded in December
- The company has grown steadily as the funded loans show a steady increase over the years
- Shorter tenure loans are more likely to get defaulted
- There was no visible correlation between verification status and the loan default
- Lesser employment tenure and more than 10 years employment tenure could default on the loan
- Loans graded F and G tend to default more. As the category progresses from A to G, risk of default also increases.
- Loans taken for small business, renewable energy and educational purposes tend to default more
- Renters are more likely to default than home-owners and people with mortaged homes
- Lesser the annual income, higher the risk of default
- Higher interest rate loans are more likely to be defaulted
- When DTI increases, loans are likely to be defaulted but only until 25. When DTI crossed 25, behaviour was contradicting.
  This might be because as dti reaches 25, it indicates borrower has become thin financially. Lenders might have become more strict in their risk
  assessment and they might not have been approving loans for people with higher DTIs.

## Technologies Used

- Python

## Acknowledgements

- References
  https://towardsdatascience.com/how-to-clean-your-data-in-python-8f178638b98d
  https://realpython.com/python-data-cleaning-numpy-pandas/
  https://pbpython.com/pandas-qcut-cut.html
  https://pbpython.com/pandas-crosstab.html
  https://towardsdatascience.com/a-complete-guide-to-plotting-categorical-variables-with-seaborn-bfe54db66bec
  https://poulami98bakshi.medium.com/univariate-and-bivariate-analysis-an-easy-guide-2139dd286d4b

## Contact

Created by @prathyu13, @KBinSAP
