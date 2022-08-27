## Loan Eligibility Prediction for Dream Housing Finance company

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 

#### Data Source:
Datahack:  https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/ <br>
Train file: CSV containing the customers for whom loan eligibility is known as 'Loan_Status' <br>
Test file: CSV containing the customer information for whom loan eligibility is to be predicted <br>

#### Technologies:
Programming Language: Python <br>
Libraries: Pandas, Scikit-learn, XGBoost, Matplotlib, Numpy <br>
Hyperparameter Tunning: Yes <br>
*Note: Do Check out project report pdf to find out how I used these algorithms.*

#### Results:
| Models             	    | Accuracy                   |
|---------------------------|----------------------------|
| Max_cross validation     :| 0.80                       |
| XGBoost without tunning  :| 0.76                       |
| XGBoost with tunning (1) :| 0.80                       |
| XGBoost with tunning (2) :| 0.75      
