# GermanBankLoan

Domain: Banking

### Context
This data set contains historical data of the customers who have taken loans from a German bank and the bank is facing issues with loan defaulters. The bank intends to build a machine learning model to predict whether the customer will default or not based on historical data

### Data Description: 
The bank has historical information on relevant features for each customer such as employment duration, existing loans count, saving balance, percentage of income, age, default status. 

The data set has 17 columns and 1000 rows. Columns are described below and each row is a customer. 

checking_balance - Amount of money available in account of customers
months_loan_duration - Duration since loan taken
credit_history - credit history of each customers
purpose - Purpose why loan has been taken
amount - Amount of loan taken
savings_balance - Balance in account
employment_duration - Duration of employment
percent_of_income - Percentage of monthly income
years_at_residence - Duration of current residence
age - Age of customer
other_credit - Any other credits taken
housing- Type of housing, rent or own
existing_loans_count - Existing count of loans
job - Job type
dependents - Any dependents on customer
phone - Having phone or not
default - Default status (Target column)

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
