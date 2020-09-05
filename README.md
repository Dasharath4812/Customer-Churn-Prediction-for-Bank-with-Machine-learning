# Customer-Churn-Prediction-of-Bank-with-Machine-learning
A Bank wants to take care of customer retention for its product: savings accounts. The bank wants you to identify customers likely to churn balances below the minimum balance. You have the customers information such as age, gender, demographics along with their transactions with the bank.

Churn prediction is a common use case in machine learning domain. If you are not familiar with the term, churn means “leaving the company”. It is very critical for a business to have an idea about why and when customers are likely to churn. Having a robust and accurate churn prediction model helps businesses to take actions to prevent customers from leaving the company.

In this project, I will use “Bank Customer Churn” dataset which is available on Kaggle.

There are 20 features (independent variables) and 1 target (dependent) variable for 28382 customers. Target variable indicates if a customer has left the company (i.e. churn=yes) within the last month. Since the target variable has two states (yes/no or 1/0), this is a binary classification problem.

The variables are:"customer_id","vintage",	"age",	"gender",	"dependents",	"occupation",	"city",	"customer_nw_category",	"branch_code", "days_since_last_transaction", "current_balance",	"previous_month_end_balance",	"average_monthly_balance_prevQ",	"average_monthly_balance_prevQ2",	"current_month_credit",	"previous_month_credit",	"current_month_debit",	"previous_month_debit",	"current_month_balance",	"previous_month_balance",	"churn"

At first glance, only customerID seems irrelevant to customer churn. Other variables may or may not have an effect on customer churn. We will figure out.

The project is structured as follows:
- Exploratory Data Analysis
- Data Preprocessing
- Model Creation and Evaluation
- Improving the Model
