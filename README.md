# PRCP-1006-HomeLoanDef
PRCP-1006-HomeLoanDef
Problem Statement

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model  to  identify the factors / customer segments that are eligible for taking loan.




Dataset Link:

Link : https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1006-HomeLoanDef.zip

 
Data Description
●	application_train.csv
○	The main file which contains the Target(1:Defaulter ; 0: Not Defaulter)
○	Static data for all applications. One row represents one loan in our data sample.
●	bureau.csv
○	All client's previous credits provided by other financial institutions that were reported to Credit Bureau (for clients who have a loan in our sample).
○	For every loan in our sample, there are as many rows as number of credits the client had in Credit Bureau before the application date.
●	bureau_balance.csv
○	Monthly balances of previous credits in Credit Bureau.
○	This table has one row for each month of history of every previous credit reported to Credit Bureau – i.e the table has (#loans in sample * # of relative previous credits * # of months where we have some history observable for the previous credits) rows.
●	POS_CASH_balance.csv
○	Monthly balance snapshots of previous POS (point of sales) and cash loans that the applicant had with Home Credit.
○	This table has one row for each month of history of every previous credit in Home Credit (consumer credit and cash loans) related to loans in our sample – i.e. the table has (#loans in sample * # of relative previous credits * # of months in which we have some history observable for the previous credits) rows.
●	credit_card_balance.csv
○	Monthly balance snapshots of previous credit cards that the applicant has with Home Credit.
○	This table has one row for each month of history of every previous credit in Home Credit (consumer credit and cash loans) related to loans in our sample – i.e. the table has (#loans in sample * # of relative previous credit cards * # of months where we have some history observable for the previous credit card) rows.
●	previous_application.csv
○	All previous applications for Home Credit loans of clients who have loans in our sample.
○	There is one row for each previous application related to loans in our data sample.
●	installments_payments.csv
○	Repayment history for the previously disbursed credits in Home Credit related to the loans in our sample.
○	There is a) one row for every payment that was made plus b) one row each for missed payment.
○	One row is equivalent to one payment of one installment OR one installment corresponding to one payment of one previous Home Credit credit related to loans in our sample.
Domain: Banking

Model Comparison Report

Create a report stating the performance of multiple models on this data and suggest the best model for production.

Report on Challenges faced

Create a report which should include challenges you faced on data and what technique used, with proper reason.








