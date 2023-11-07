# Lending Club Case Study
> A consumer finance company that caters to urban customers must evaluate loan applications to decide whether to approve them or not. This decision involves assessing two types of risks:
> When an applicant is deemed likely to repay the loan, rejecting the application means the company loses potential business.
Conversely, if the applicant is likely to default and not repay the loan, approving it could result in financial losses for the company.


## Table of Contents
* Problem Statement
* EDA - Approach
* Cleaning the Data
* Analysing the Data (Univarite Analysis, Segemented Univariate Analysis, Bivariate Analysis, Dervied Metric Analysis)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The primary objective of this case study is to pinpoint high-risk loan applicants to minimize the number of such risky loans and consequently reduce credit losses. 
- To achieve this, we must identify the key factors or variables that strongly correlate with loan defaults, serving as reliable indicators of potential default.
- WWe have been given a loan dataset that includes comprehensive information about all loans disbursed between 2007 and 2011. 
- Additionally, a data dictionary has been provided, offering descriptions and explanations for the attributes or variables present in the dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Approach
- We have taken the loan dataset and imported it into a pandas DataFrame, where we performed data cleansing tasks such as handling missing values, outliers, standardization, and removing redundant information.
- Subsequently, we proceeded to systematically analyze the data to determine the key factors contributing to loan defaults.
- Our analytical process involved various stages, including univariate analysis, segmented univariate analysis, bivariate analysis, and ultimately, an examination of derived metrics. 
- Throughout each of these stages, we pinpointed the variables that exhibited correlations with loan defaults, and we thoroughly documented all our findings.
  
## Conclusions
- Customers who opt for a 60-month loan term and later default tend to have borrowed larger amounts compared to those with a 36-month loan term. 
- Highly experienced borrowers with higher annual incomes are more likely to repay their loans.
- Borrowers with mortgages or those living in rental houses, with high interest rates and larger loan amounts, are more likely to default.
- Loans taken for housing purposes with more inquiries in the last 6 months are more likely to default.
- Loans taken for debt consolidation with more open credit accounts are more likely to default.
- Credit card users with higher revolving balance utilization are more likely to default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Acknowledgements
We have completed a project as part of an AI/ML Executive Program with IIT Bangalore


## Contact
Created by https://github.com/Sai-Krishna-Rali - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
