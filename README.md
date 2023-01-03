# ANALYSIS OF LOAN DATA FROM PROSPER
## by RHODA OJETOLA


## Dataset

> This dataset consists of loan listings, borroers, lenders, borrowers rate, borrowers income e.t.c from the loan comapany Prosper Marketplace Inc. which was the first peer-to-peer lending marketplace in the United States established in 2005. Prosper ha s facilitated over 21 billon loans to over 1.3 millon people.This data set contains 113,937 loans with 81 variables on each loan, The data set was gotten from the udacity server.

### Python Libraries used:
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Summary of Findings

> In the exploration, i found that there was a strong relationship between Borrower Annual Percentage Rate(APR), Borrower Rate (Interest Rate) and Lender Yield. 
> There was also a linear relationship and negative correlation betweem Borrower apr and credit scores.
>  There is also a linear relationship between Borrower APR and Debt To Income Ratio, when Debt To Income was plotted on cuberoot scale (transformed scale)
> Surprisingly higher loan amounts are associated with low Borrower APR. However high loan amounts are listed by borrowers with high income.
so there also a negative correlation between income and borrower APR.
> I also checked for the relationship between Prosper Rating and Home ownership (IsBorrowerHomeOwner), it look like the distribution of low risk rating had low number of home owner but the lowest risk had the least number of borrowers who did not have home.

> From the visualizations carried out in this Exploratory Analysis, Borrowers who have high income, high credit score, low Debt to income Ratio and low Number of delinquencies will have low risk rating associated with them and this will probably lead to low Borrower APR *While* Borrowers who have low income, low credit score, high Debt to income Ratio and high Number of delinquencies will have low risk rating associated with them and this will probably lead to high Borrower APR.

## Key Insights for Presentation

> Borrower Annual Percentage Rate (APR) is affected mainly by the risk associated with the Borrower asking for the loan, And what plays a major role to determine that risk is Credit Score of the borrower. A better credit score that is high scores gives lenders and investors the impression that there less risk associated with the borrower and the loan, This will lead to a low Borrower APR and also more investors on the Prosper Loan listing. When the Borrower Credit Score is low, it suggests to lenders that there is a lot more risk associated with the borrower and the loan, This leads to a high Borrower APR and likely less investors.
> For this presentation we also will look at the relationship between Borrower APR and Credit Scores with categorical variables Prosper Rating which is used to measure the risk and Home ownership. Borrowers with high credit scores are likely to be homeowners and less risk borrowers so this will lead to low Borrower APR While Borrowers with low credit scores are less likely to be homeowners and high risk borrowers so this will lead to high Borrower APR.
