# EDA_Loan_Default
This is my first EDA project.

# Problem Statement
The loan providing companies find it really difficult to sanction loans to the people due to their insufficient or non-existent credit history. Which is why, some of the consumers use it as their advantage by becoming a defaulter. Here, I was given the dataset with 3 files.
Application_data.csv - contains all the information of the client at the time of application.The data is about whether a client has payment difficulties.
Previous_application.csv - contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
Columns_description.csv- Contains data dictionary which describes the meaning of the variables.
And, I have to use EDA to analyse the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected.

# My Approach
When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The data given contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:
The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,
All other cases: All other cases when the payment is paid on time.

Here:
We need to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected.
Also, we need to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. So that the company can utilise this knowledge for its portfolio and risk assessment.

# Summary

‘Application_data’ Dataset Analysis:
- As we can see, applicants with secondary education type are the highest non-defaulter
  applicants. My Conclusion from application_data.csv Analysis: NAME_INCOME_TYPE - Working
  and Commercial associates are the highest non-defaulters and Commercial associates are the
  highest defaulters.
- GENDER_CODE - Females have the highest non-defaulters rate as compared to Males
- INCOME_RANGE - People having annual income ranging in between 1L-2L are the highest nondefaulters
  as compared to people with annual income range of 0-1L.
- CONTRACT_TYPE - Maximum non-defaulter loans were 'Cash loans'.
- AGE_RANGE - Most of the Applicants with age Above 60 are non-defaulters.
- EDUCATION_TYPE - Applicants with secondary education type are the highest non-defaulters.

‘Previous_application’ Dataset Analysis:
- People with more children and less income are likely to default more.
- All the defaulters belong to lower income group.
- Maximum records were found with Missing ‘Loan Purpose’
- Among the existing records, Maximum applications have the purpose of ‘Repair”

'My Overall Analysis' :
- People with lower total income are most likely to default. Please, avoid approving these loans.
- Applications with applicant having Lower secondary education should be rejected.
- Maximum People with a secondary education are non-defaulters.
- Working type applicants are less likely to default.
- Applicants around age 30-45 are the highest among non-defaulters.
