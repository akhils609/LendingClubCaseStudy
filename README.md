# Project Name
> Lending Club Case Study
>> by Akhil Suresh and Irfan Khan Mohammed


## Table of Contents
* Initial Phase
* Data Preprocessing
* Data Cleaning
* Data Transformation
* Data analysis
* Univariate Analysis 
* Bivariate Analysis
 
## General Information
- Provide general information about your project here.
- What is the background of your project?
Solving this assignment will give an idea about how real business problems are solved using EDA.
In this case study, apart from applying the techniques we have learnt in EDA, we will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
- What is the business problem that your project is trying to solve?
To make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- What is the dataset that is being used?
A CSV file was shared name loan.csv


## Conclusions
- Conclusion 1 from the analysis
Average loan amount is around 11235.
Average interest rate is around 12%
Average Total Amount is around 12172.
Average Annual Income is around 69000.
The mean value is 61049 and it falls under 50th and 75th quantile.
Around 83% loan are fully paid, 14% are Charged off (delinquent) and 3% are Current..
Top 5 Loan Purpose round off are as follows:
	Debt_consolidation = 47%
	credit_card = 13%
	Other = 10%
	home_improvement = 7%
	major_purchase = 6%
Top 3 Home Ownership round off are as follows:
	Rent = 49%
	Mortgage = 43%
	Own = 8%.
Close to 96% have 0 public record bankruptcies.
Top 3 LC Grade category are as follows:
	B = 30%
	A = 26%
	C = 20%
Loan amount and Funding are not equal. Most likely Customers with lower loan amount to receive higher funding (within the loan amount).
Seems like the higher the income lower is customer opting for loan.
Seems like Grade G customers has highest minimum estimator.
From above joint plot we noticed:
The correction between Loan amount and Defaulters is picked at 5000, 10000 and 15000.
We noticed higher acceptance compared to rejection.
Year on year on monthly basis funding amount has been increasing.
Funding is highest in December and lowest in June.
Loan taken for small business purposes see higher charge off.
Loan application with Grade G has higher charge off percentage.
NV(Nevada) state has significantly higher charge off percentage and NE(Nebraska)'s higher charge off due to lower total.
Customers with 2 public bankruptcies have
higher charge off percentage.
Its 16%+ against 25% Charged off customers.
Its 0 to 20000 against 20% Charged off customers.
No huge variations in the averages for the all the imp numeric column.
For small business purpose has higher average loan amount.
10 to 15 highest range under which accounts are opened against Fully Paid Loan status.
Highest Loans are taken in the 10th year followed by 1st year.


## Technologies Used
Pandas Version: 2.0.3
Numpy Version: 1.25.2
Seaborn Version: 0.13.1
matplotlib version 3.7.1
Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@akhils609] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->
