# Bank Marketing Campaign : EDA
## Introduction
The bank provides financial services such as savings accounts, current accounts, debit cards, etc. to its customers. In order to increase its overall revenue, the bank conducts various marketing campaigns for its financial products such as credit cards, term deposits, loans, etc. These campaigns are intended for the bank’s existing customers. However, the marketing campaigns need to be cost-efficient so that the bank not only increases their overall revenues but also the total profit.

The bank conducted a telemarketing campaign for one of its financial products ‘Term Deposits’ to help foster long-term relationships with existing customers. The dataset contains information about all the customers who were contacted during a particular year to open term deposit accounts.

### What is the term Deposit?
Term deposits also called fixed deposits, are the cash investments made for a specific time period ranging from 1 month to 5 years for predetermined fixed interest rates. The fixed interest rates offered for term deposits are higher than the regular interest rates for savings accounts. The customers receive the total amount (investment plus the interest) at the end of the maturity period. Also, the money can only be withdrawn at the end of the maturity period. Withdrawing money before that will result in an added penalty associated, and the customer will not receive any interest returns.

## Problem Statement:
Target is to do end to end EDA on this bank telemarketing campaign data set to infer knowledge that where bank has to put more effort to improve it's positive response rate.

## Data Set Characteristics:
Number of Observations in both train and test data set : 49732

**Number of features :**

16 (numeric/categorical) independent features.
1 (target) dependent feature.

**features related to bank client data:**

1. Age: Client’s age.
2. Job: Client’s type of job.
3. Marital: Client’s marital status, divorced means divorced or widowed.
4. Education: Client’s education.
5. Default: Does the customer have credit in default.
6. Balance : Client balance.
7. Housing: Client has a housing loan.
8. Loan: Client has a personal loan.

**features related to last contact of the current marketing campaign:**

9. Contact: Contact communication type (telephone or cellular).
10. Day : Last contact day of week.
11. Month: Last contact month of year.
12. Duration: Last contact duration in seconds. If duration is 0s, then we never contacted a client to sign up for a term deposit account.
13. Campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
14. Pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
15. Previous: number of contacts performed before this campaign and for this client (numeric)
16 Poutcome: outcome of the previous marketing campaign (categorical: ‘failure’,‘nonexistent’,‘success’)

***Output feature (target):***

17. y - has the client subscribed a term deposit? (binary: ‘yes’, ‘no’)
