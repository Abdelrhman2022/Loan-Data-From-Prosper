# Loan Data from Prosper
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

# Conclusion
During investing the ProsperRating (Alpha) and the ProsperScore as it relates to the BorrowerRate I could know an explanation for why the ProsperScore wasn't as highly correlated to the BorrowerRate. It is opposite the other credit risk features must use different criteria in coming up with its value

A surprising interaction is that the borrower's APR and loan amount is negative correction when the Prosper ratings are from HR to B, but the correlation is turned to be positive when the ratings are A and AA. Another interesting thing is that the borrower APR decreases with the increase of borrow term for people with HR-C ratings. But for people with B-AA ratings, the borrower's APR increase with the borrowing term. 

BorrowerRate increases for longer Term loans when split up by ProsperRating (Alpha). The opposite relationship would be expected as longer-term loans generally carry a lower risk profile and have a longer time to accrue interest

In exploring how the interest rate of a loan is affected by the loans Term (length of loan) I discovered that under every ProsperRating shorter term loans had a lower interest rate. Unsurprisingly those with a higher/better ProsperRating had a lower interest rate.

# Limitations
Exploratory Data Analysis is a good way to know the data using vivid and interesting visualizations. However, to make a final statement about the relationships among variables we need to conduct the statistical tests and build predictive models.

# Resources
* [Example Project](https://github.com/loeakaodas/dand_communicate_data_findings/tree/master/Example%20Project) from Udacity.
* Prosper [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)
* seaborn documentation
* [Geeks for Geeks](https://www.geeksforgeeks.org/)
