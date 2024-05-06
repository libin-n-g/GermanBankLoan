# GermanBankLoan

Domain: Banking

### Context
This data set contains historical data of the customers who have taken loans from a German bank and the bank is facing issues with loan defaulters. The bank intends to build a machine learning model to predict whether the customer will default or not based on historical data

### Data Description: 
The bank has historical information on relevant features for each customer such as employment duration, existing loans count, saving balance, percentage of income, age, default status. 

The data set has 17 columns and 1000 rows. Columns are described below and each row is a customer. 

1. checking_balance - Amount of money available in account of customers
2. months_loan_duration - Duration since loan taken
3. credit_history - credit history of each customers
4. purpose - Purpose why loan has been taken
5. amount - Amount of loan taken
6. savings_balance - Balance in account
7. employment_duration - Duration of employment
8. percent_of_income - Percentage of monthly income
9. years_at_residence - Duration of current residence
10. age - Age of customer
11. other_credit - Any other credits taken
12. housing- Type of housing, rent or own
13. existing_loans_count - Existing count of loans
14. job - Job type
15. dependents - Any dependents on customer
16. phone - Having phone or not
17. default - Default status (Target column)

## Project Structure

- `MachineLearningReport.pdf`: PDF report summarizing the project and its findings.
- `Project-EDA.ipynb`: Jupyter notebook containing the exploratory data analysis (EDA) process and some preprocessing like One hot encoding etc.
- `Project-EDA.html`: HTML version of the EDA notebook for easier viewing.
- `Project-Models.ipynb`: Jupyter notebook containing the machine learning modeling process and evaluvation of models.
- `Project-Models.html`: HTML version of the modeling notebook for easier viewing.
- `preprocessed_credit.csv`: Preprocessed dataset used in the analysis which is result of preprocessing in Project-EDA.ipynb.
- `credit.csv`: Original dataset used in the analysis.

# References
 - [https://www.analyticsvidhya.com/blog/category/algorithm/](https://www.analyticsvidhya.com/blog/category/algorithm/)
 - [https://scikit-learn.org/stable/modules/classes.html](https://scikit-learn.org/stable/modules/classes.html)
 - https://lightgbm.readthedocs.io/en/latest/pythonapi/lightgbm.LGBMClassifier.html
 - https://www.analyticsvidhya.com/blog/2021/06/5-techniques-to-handle-imbalanced-data-for-a-classification-problem/
 - https://catboost.ai/en/docs/concepts/python-reference_catboostclassifier
