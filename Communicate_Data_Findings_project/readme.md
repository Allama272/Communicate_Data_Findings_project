# Prosper Loan Data Exploration

## Dataset
 The data consists of information (81 columns) about 113937 loan, including term, loan original amount, annual interest rate, and others. 
 The data set can be found at: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000
 and the Prosper Data Dictionary to Explain Dataset's Variables can be found at: https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000

## Summary of Findings
The main findings of this analysis were:
- As the prosper score increases the annual percentage rate decreases with a strong corelation.
- The relation between the LoanOriginalAmount and the BorrowerAPR is negetive, although not strong.
- There is a weak corelation between AvailableBankcardCredit and BorrowerAPR even after removeing the outliers.
- For all income ranges, the longer the term the more money will be borrowed. 
- Almost always the higher income range will have a lower BorrowerAPR in any ProsperScore regardless of the income range

## Key Insights for Presentation
In the presentaion, the focus is mostly on the best variables that has a corelation with the annual interest rate (BorrowerAPR). I showed the corelation between Annual Interest Rate and three variables (Prosper Score, Loan Original Amount, and Available Bank card Credit). For the Prosper Score, I showed a barplot explaining that there is a negetive corelation between Prosper Score and Annual Interest Rate. I then showed a heatmap with that shows that this reletaion is present regardless of the income range. Using scatter plot, I showed that there is a weak corelation between the loan original amount and the annual interest rate. Lastly, I showed that there is also a weak relation ship between the available bank card credit and the annual interest rate using a scatter plot.
