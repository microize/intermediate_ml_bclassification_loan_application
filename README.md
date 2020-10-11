# Binary classification - loan application (accepted/rejected)

# Context
Credit risks refer to the risks of loss on a debt that occurs when the borrower fails to repay the principal and related interest amounts of a loan back to the lender on due dates.
When a bank receives a loan application, based on the applicant’s profile the bank has to make a decision for its approval or rejection. There are two types of risks associated with this decision:

* If the applicant has good credit risk, i.e. is likely to repay the loan, then rejecting the loan results in a loss to the bank
* If the applicant has bad credit risk, i.e. is unlikely to repay the loan, then approving the loan results in a loss to the bank
It may be assumed that the second risk is a greater risk, as the bank (or any other institution lending the money to an untrustworthy party) had a higher chance of not being paid back the borrowed amount.

So it's on the part of the bank or other lending authority to evaluate the risks associated with lending money to a customer.

# Hackathon Link
https://dphi.tech/practice/challenge/38#problem

# Problem Statement
Imagine a bank in your locality. The bank has realized that applying data science methodologies can help them focus their resources efficiently, make smarter decisions on credit risk calculations, and improve performance.

Earlier they used to check the credit risk of the loan applicants manually by analyzing their bank-related data, which used to take months of time. But this time they want a smart data scientist who can automate this process.

# Objective
You are required to build a machine learning model that helps you predict the credit risk of the loan applicants.

# Evaluation Criteria
Submissions are evaluated using Accuracy Score.

# Data Description
There are 20 attributes in the dataset. Some of them are mentioned below:

1. checking_status: Status of the existing checking account
2. duration: Duration in month
3. credit_history: Credit history of the applicant
4. purpose: Purpose of taking the earlier loans
5. employment: Present employment since
6. installment_commitment: Installment rate in percentage of disposable income
7. personal_status: Personal status and sex
8. other_parties: Other debtors/guarantors
9. residence_since: Present residence since
10. other_payment_plans: Other installment plans
11. existing_credits: Number of existing credits at this bank
12. class: The target variable(good, bad)
