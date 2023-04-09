# AllLife Bank Personal Loans Project

Background and Context

AllLife Bank is a US bank that has a growing customer base. The majority of these customers are liability customers (depositors) with varying sizes of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).

A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio.

For this project, I have to build a model that will help the marketing department to identify the potential customers who have a higher probability of purchasing the loan.

Objective

To predict whether a liability customer will buy a personal loan or not. Which variables are most significant. Which segment of customers should be targeted more. (Remember: in logistic regression, the dependent variable should be categorical and independent variables can have a mix of continuous and categorical variables. In linear regression, the dependent variable should be continuous.)

Data Dictionary

ID: Customer ID

Age: Customer’s age in completed years

Experience: #years of professional experience

Income: Annual income of the customer (in thousand dollars)

ZIP Code: Home Address ZIP code

Family: the Family size of the customer

CCAvg: Average spending on credit cards per month (in thousand dollars)

Education: Education Level. 1: Undergrad; 2: Graduate;3: Advanced/Professional

Mortgage: Value of house mortgage if any. (in thousand dollars)

Personal_Loan: Did this customer accept the personal loan offered in the last campaign? (dependent variable)

Securities_Account: Does the customer have securities account with the bank?

CD_Account: Does the customer have a certificate of deposit (CD) account with the bank?

Online: Do customers use internet banking facilities?

CreditCard: Does the customer use a credit card issued by any other Bank (excluding All life Bank)?

# AllLife Bank Data Report

Executive Summary

This report analyzes prediction of buying personal loans from AllLife Bank to identify the key factors that impact chances of buying personal loans. This analysis found that the most significant were income, family, education and average credit card spending. I recommend that AllLife Bank focus on targeting people with low income, large family size, and average credit card spending of $2,700 or more.

Introduction

The purpose of this report is to predict which variables impact customers buying personal loans from AllLife Bank. The data was collected from customer surveys and includes responses from over 5,000 customers. The objective of the analysis is to predict whether a liability customer will buy a personal loan or not. Which variables are most significant. Which segment of customers should be targeted more.

Methodology

The data was collected from customer surveys conducted by the bank. The data was pre-processed and cleaned to remove any invalid or missing data. The variables used in the analysis include age, Experience: #years of professional experience, Income: Annual income of the customer (in thousand dollars), Family: the Family size of the customer, CCAvg: Average spending on credit cards per month (in thousand dollars), Education, Mortgage: Value of house mortgage if any (in thousand dollars), personal loan, Securities_Account, CD_Account, Online (Do customers use internet banking facilities?), and CreditCard (Does the customer use a credit card issued by any other Bank (excluding All life Bank)). I assumed that the data was representative of the total customers from AllLife Bank.

Invalid data was identified and removed from the dataset during the pre-processing and cleaning stage. Invalid data was defined as any data that was missing or had errors, such as incorrect formatting or outliers that were not consistent with the majority of the data. The percentage of invalid data removed from the dataset was 1%. This percentage was not statistically significant and did not have a significant impact on the analysis.

Results

In this analysis, it seems that income, family, education and average credit card spending had were the most significant factors from the decision trees.
Descriptive statistics and visualizations of the data showed that 94% of customers did not buy personal loans, while 9.6% of them did buy personal loans at AllLife Bank. It is observed that the more professional experience the customers have, the more likely there will be older people applying for personal loans. Income and the amount of money spent on credit card also have a strong correlation of 0.64, according to the bivariate analysis. If a customer has income of $98,000 dollars or more, there's a very high chance the customer will not be buying personal loans. If a customer has income of $98,000 or less and they spend around $2,950 or less, there is a high chance that they will buy personal loans. Also, it is important to note that a customer with an undergraduate degree or lower with an income of $98,000 or lower have more chances of buying personal loans.

Discussion

The results of this analysis suggest that income, family, education and average credit card spending are the key factors that impact customers buying personal loans at AllLife Bank. Improving these factors could lead to higher personal loans turnout rate and increased customer loyalty. Furthermore, here are some recommendations:

•	Income is one of the significant predictors of salary. AllLife Bank should implement guidelines to ensure that customers can buy personal loans based on their income. The bank should target specifically people with income of $98,000 or less.

•	There are more chances of people buying personal loans, if they are around the age of 35 years old.

•	As we saw in this analysis that the average amount of money spend on credit cards was $1,900. People who spent more than $2,700 might increase chances of customers buying personal loans.

•	If a customer has income of $98,000 or less and they have undergraduate education or less, there is a high chance that they will buy personal loans.

Conclusion

This analysis identified income, family, education, and average credit card spending as the key factors that impact customers buying personal loans from AllLife Bank. I recommend that the bank focus on utilizing these factors to increase customers buying personal loans and increase loyalty. The data has some limitations, but these findings provide valuable insights into the factors that are most important to these customers.
