# Exploration of Loan Prosperty
## by (Abdel Karim Lamiss MPONDO)


## Dataset

Our dataset contains information on peer-to-peer lending facilitated by Prosper Lending Company.
It initialy contains 81 columns. To do this analysis, we took the thirteen columns :
- Term
- LoanStatus
- BorrowerRate
- ProsperRating (Alpha)
- ListingCategory (numeric)
- EmploymentStatus
- DelinquenciesLast7Years
- StatedMonthlyIncome
- TotalProsperLoans
- LoanOriginalAmount
- LoanOriginationDate
- Recommendations
- Investors

Since Prosper has only been using its own Prosper Rating since 2009, we have a lot of missing values in the ProsperRating column. We removed its missing values and filled missing values in TotalProsperLoans column by **0**.


## Summary of Findings

Most of the loans in the dataset are actually current loans. Overdue loans are divided into several groups based on the length of the delay in payment. The other large portion is completed loans, defaulted loans jeopardize a minority, but written-off loans also jeopardize a substantial amount.

The majority of borrowers are employed and all other categories represent a small portion of borrowers. In a small group, full time is the highest, after which the freelancers are there and so on. 

The most frequently rating is "C".

The monthly income distribution still has a noticeable right skew, but now we can see that the mode is around 5000.

The most common rating among loans in default is actually "D". And the highest grade among the completed is also "D" and the second highest is "A" and so on.

"debt consolidation" has the highest frequency among all.

We can say that "employees" are taking more loans.

We can tell that "Defaulted Loans" tend to be smaller than "Completed Loans".

The lower coasts seem to have larger proportions of people with the employment status "Not employed", "Self-employed", "Retired" and "Part-time".

From the graph above, we can tell that "employees" tend to take the largest loan amounts.

With the exception of the lowest ratings, defaulted credits tend to be larger than completed credits. Most defaulted loans come from people with low prosperity ratings.

With the exception of the lowest grades, employees tend to be more important than completed credits. Most employees have a low prosperity rating.

There are 5 charts in the second which have many highs and lows other than all. There is no substantial difference for the default rates in the different categories broken down by rating.

With the exception of automotive, business and home improvement do not average nearly evenly between them. The business category tends to have a higher amount.


## Key Insights for Presentation

We tried to understand which features can be used to predict credit default. Also, we wanted to check what are the main factors related to credit score prosperity. We believe borrowers' Prosper rating will have the greatest impact on default risk. We also expected the loan amount to play a major role and perhaps the credit category. Prosperity score would depend on reported income and employment status.

The monthly reported income distribution is very awkward: with lots of outliers and a very wide range, but it was still skewed. The majority of borrowers are employed and all other categories a small portion of borrowers and most loans in the data set are actually outstanding loans.

The majority of credits are in fact credits in progress. Since our primary objective was to define the determinants of loan outcome, we did not focus on active loans.

The variable list category is configured as numeric and most of the values have a very low frequency, for easier viewing, so we changed it to a category and reduced the number of categories.

In loan status versus loan amount, defaulted loans tend to be smaller than once-completed loans. The employment status of people with lower ratings tends to be "Not employed", "Self-employed", "Retired", or "Part-time".

Our initial assumptions have been reinforced. Most defaulted credits come from people with a low Prosper rating and the Business category tends to have a higher amount.

An interesting finding is that past due credits for people with high prosperity ratings tend to be larger than completed credits.
