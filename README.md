# (ProsperLoan Dataset Exploration)
## by (Caleb Omariba)


## ProsperLoan Dataset 

The dataset consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. 
The data features information can be found [here ](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)
In my analysis i focused on 10 key features which i found interesting to investigate.

## Summary of Findings
In the exploration I found out that their was a strong relationship between the BorrowerAPR and the LenderYield.Most of the majority of the loans in our data set were current loans whereby I observed that the majority of the loans were those with the 3 years term period.The profession that was leading in borrowing loans apart from the others category was the professionls followed by computer programmers . I found out that the leading reason given by borrowers when they apply for loans was to pay other why debts incurred by them elsewhere.

It was also noted that people with most loans are those earning an annual salary of a range of 25000-49000 $.Most completed and current loans have  a BorrowerAPR  of about 20% which is lower compared with other loan status categories.

I also observed that the loan original amount have -ve correlation of -0.323 also we can see a correlation with the lenderyield of -0.328 with the original loan amount. Most of the features seemed to have weak linear correlations.



## Key Insights for Presentation
In the presentation I focused on what factors affected the BorrowAPR from which i noticed that most people with high ProsperScore ratings had lower interest rates charged on their loans.
Also the correlation between Borrower APR and LenderYield. I first begin by plotting the general histogram to show the general distribution of numeric variables. I go deeper to check the distribution of the BorrowerAPR. I also plot a count plot to show the distribution of the ProsperScore using seaborn.I have also plotted an histogram to show the distribution pattern of the LenderYield.

I have also plotted a scatterplot with a column bar to show the corretion of the various features and finally a correlation heatmap matrix to reveal the relationship between various features in the exploration. 