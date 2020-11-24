# Bank Data Exploration

## Dataset
- Name: prosperLoanData.csv
- Definition: Loan Data from Prosper
- Source: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
- Detail: This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate),current loan status, borrower income, and many others<br>

## Summary of Findings

In the exploration, I found the following under Univariate, Bivariate and Multivariate Exploration:-
### 1. Univariate Exploration
- Original Loan amount is right skewed. Most of the loan amount are in range of 0-5000.
- Most of the Loan status is Current. Apart from it we can see alot of completed loan case.
- 54.4% of the borrower's are homeowner.
- Most of the borrowers are employed amd full-time worker.
- There are very few people(4.7%) with income less than 24,999.
- Loans with "AA" category are with lesser count
- There are alot of borrower's with prosperScore less than 6.0. Based on this we can say loan was even provided to people with high risk score.
- Most of the borrower's didn't specify there occupation that was given in form, they wrote Other.

### 2. Bivariate Exploration
- Negative correlation between BorrowerRate and Prosper Score, means lower the prosper rate, higher will be the borrower rate
- Higher loan amount is associated with high monthly payment, as they are have strong positive correlation.
- Loan original amount and monthly loan payment is highly positive correlated,
- Borrowers interest rate and proper score are highly negatively correlated,
- Borrower interest rate and Loan original amount are negatively correlated.
- Full-time employs have generally high prosper rating than others.
- Self-employed people have low prosper rating
- Executives, Pharmacist, Doctors and Judge have large loan amount in comparision to other occupants
- People with high Income range took high loan amount.
- Prosper Rating B and C have most number of people who are employed.
- Borrowers with salary range are between  50,000− 74,999 are mostly in prosper rating of A, B, C or D.

### 3. Multivariate Exploration
- Based on the Prosper Rating we can conclude that large amount of amount of loan is easily provided to those who have high monthly salary and are employed or full-time worker.
- Employment Status And Monthly Salary can be considered few parameter that affected Prosper Rating.
- Employed, Self-employed and full-time borrowers generally have high monthly amount who takes loan.
- Employed people tends to take larger loan amount in comparision to other Employment status irrespective of their Income Range.
- People who are self-employed and have decent salary between  75000− 99999 apply for loan to fulfill their needs.
- The non-homeowner tend to have a higher interest rate, and thus lower prosper rating. On the other hand homeowner tends to have lower interest rate and higher prosper rating. So we can conclude that homeowner are the safest bet when gving a loan. We can see that HR prosper rating applicants have higher interest rates


## Key Insights for Presentation
- Large amount of loan is easily provideed to those will high income range and they have generally better prosper rating than other, thus their borrower interest rate would alse be lesser than others.
- Full-time employs have generally high prosper rating than others, and have better chance of getting loan easily with lesser borrower interest rate.
- Self-employed people have low prosper rating, thus it's hard for them to get high loan amount with lesser borrower interest rate.
- Employment Status And Income Range can be considered few parameter that affected Prosper Rating.
- We observe that non-homeowner tend to have a higher interest rate, and thus lower prosper rating. On the other hand homeowner tends to have lower interest rate and higher prosper rating. So we can conclude that homeowner are the safest bet when gving a loan. We can see that HR prosper rating applicants have higher interest rates
- Borrowers interest rate and proper score are negatively correlated. With lower prosper score, the borrower interest rate tends to increase. Therefore, more the prosper score will be, lesser will be the interest rate.
- Borrower interest rate and Loan original amount have moderate negative correlation. Thus we expect that for higher loan amount, the borrower interest rate will be lesser.
