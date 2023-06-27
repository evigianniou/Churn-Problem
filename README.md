# Churn-Problem
Solving the Churn Problem of Maastricht Telecom
1. Problem
The problem of churn is a problem when a number of individuals move out of a collective
group. It is one of the main problems that determine the steady-state level of customers
in any type of business.
Recently a large number of customers has left Maastricht Telecom. To address this
problem Maastricht Telecom provides customer data to solve two important tasks:
 Descriptive task: Characterize loyal and churn customers and propose a focused
customer retention program. (This can be done through visualization, descriptive
models etc. )
 Predictive task: Find a model that identifies churn customers. Then:
o Select 300 customers using that model from a separate test set and report
the number of true churn customers among them.
o Calculate the expected costs for Maastricht Telecom for one month when
using your model on the test set if:
 every customer predicted as churn will get a gift of 10 euro and
 every true churn customer predicted as loyal will cause a loss of
64 euros (an average month subscription)
   
Results

Descriptive Task

Characteristics of loyal and churn customers:
Customers taking a longer contract(2 years contruct)are more loyal to the company and tend to stay with it for a longer
period of time.Customers who dont churn tend to stay for a longer tenure with the telecom company Customers who have month to month contract have a very high churn rate.
Senior citizens have almost double the churn rate than younger population When monthly charges are high a big percent of customers churn.The absence of online security is also
a reason that make customers to churn. Most churn customers are those who have contract only for a month (this is logical as after the end of their contract is most possible to leave
their "product" than others who have longer contracts), and those who dont have services like tech support and online security and also those who use fiber optic internet
servise(which surprisingly means faster internet) because probably it is more expensive and also because the most of churn customers are senior citizens who probably dont need
very fast internet. Proposed system The system I would suggest to the Telecom company is to always make a two-year contract with its customers, to have DSL internet service and
to include tech support in the contract.

Predictive Task:
The predictive model used for our test set is Gradient Boosting Algorithm with smote sampling and tree based feature selection. 

The expected cost for the company in one month will be 5709 Euros
