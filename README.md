# PROSPECT LOAN DATA EXPORATION
## by Haron Nyamai Wambua


## Dataset
This dataset consists 113,937 rows  and 81 columns giving information on loans provided. The columns or features include:loan amount, borrower rate (or interest rate), current loan status, borrower income, and many other features relating to loans. The dataset information can be found [Dataset information](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

Before doing the exploration, I selected the most important features as well as the target feature for the exporation I was about to do. I desired to know what factors affect the amount of interest rate charged to a borower of loan. The following were the steps taken:

1. The target feature was borrowerrate. These were the features selected: Loanstatus, ProsperRating (numeric), BorrowerState, Occupation, EmploymentStatus, EmploymentstatusDuration, IsBorrowerHomeOwner, CurrentlyInGroup, CurrentCreditLines, TotalInquiries, TotalTrades, IncomeRange, DebtToIncomeRatio, LoanOriginalAmount, LoanOriginalDate, Investors. 

2. From the selected features both the ordinal and nominal features were converted into categorical datatypes as well as date column was converted into datetime datatype.



## Summary of Findings

Most of the features were normaly distributed showing a slight positive skew.
From the analysis done, there were no strong correlation between the features, however, there was seen some interesting trends such as:
1. The more the loan amount the lower the interest rate
2. The more the salary/income the higher the chance of getting a high amount of loan.
3. Those who are full time employed were more likely to complete paying their loan in time and hence appeared to have more high amount loans.
4. The more the investors the more likely a loan is to be paid on time.


## Key Insights for Presentation
From the plots made and especially the facet grid on the multivariate analysis, I discovered that the more the amount one earns, the higher the chance of getting a huge amount of loan at a lower interest rate (borrowerrate).
It also appeared that as the number of investors increase, the interest rate went down. It was also clear that very few people who are employed full time had their loan status past certain due time. Again it was noted that those that had loan status past due date, majority had less than 500 investors. Again, it was evident that very few of the retired class of employment status had their loan status past due dates just like the full time employees.