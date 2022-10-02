# PROJECT Communicate Data Findings
Choose a dataset, either your own or a Udacity-curated dataset, and perform an exploratory data analysis using Python. Then, create a presentation with explanatory plots that conveys your findings.

# Loan Data (from Prosper) Exploration

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

* This [data dictionary](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1664203594297786&usg=AOvVaw1M4pBR3jcCIzQ0W1t2kisP) explains the variables in the data set.

## Summary of Findings

In the exploration, I found that the most contracted loan term length is `36 months` with more than 80000 contracts. 
The `BorrowerAPR` distribution is slightly normal, with a standard deviation of `0.080364` the median value of the BorrowerAPR is `0.209760` and it is closest to the mean `0.218828`. It means that the BorrowerAPR is really good for loans. Most of the loans are for `Debt Consolidation`. Really inspiring and almost all loans are funded by one investor(More than 25000 loans.). Looks like there needs to be an employee for some time (about 100 months) in order to the a borrower, assuming your employement come with high revenues. (to be able to be Homeowner.)

## Key Insights for Presentation

For the presentation, I found that there needs to be an employee for some time (about 100 months) in order to the a borrower, assuming your employement comes with high revenues. (to be able to be Homeowner.) For lower `IncomeRange`(under $25.000) it is really difficult to have loan with even a little amount`LoanOriginalAmount`, with even a lower `ProsperRating (Alpha)` score and it is merely impossible to have a loan no matter the `ProsperRating (Alpha)` score if your `IncomeRange` is null. The `BorrowerAPR` range tend to be lower when the `IncomeRange` tend to be higher and the `ProsperRating (Alpha)` score higher. The `LoanOriginalAmount` range tend to be higher when the `IncomeRange` tend to be higher and  the `ProsperRating (Alpha)` score higher