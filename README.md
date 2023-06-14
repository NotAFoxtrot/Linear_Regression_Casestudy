# Linear_Regression_Casestudy

## What's Affecting Your Loan Interest Rate?

Our case study looks to investigate how certain contributing factors affect a person's interest rate when taking out a loan.


### Background

The dataset we used to compile this information contains the following features, as well as our target feature 'interest_rate':

Factors that affect your interest rate:
* Amount Requested
* Amount Funded by Investors
* Loan Length
* FICO Score

### How things relate

Using a scatter matrix we were able to see how factors in the dataframe correlated to one another:

![scatter_matrix](photos/scatter%20matrix%20no%20titles.png)

For the purposes of our presentation the image has had it labels removed to be reformated correctly via third party tools outside of python libraries. 

It becomes immediately obvious that one section seems to share the closest correlation with interest rates, that column being the FICO Score.

Upon closer examination, using a seaborn regression plot we can get a better understanding of that correlation:

![sns_regression](photos/Fico%20vs%20Intrest%20Scatter%20Plot.png)

As you can see the higher your credit score the lower your overall interest rate tends to be.

### Conclusion 

Future Analysis:

* A deeper dive into FICO score determination
* FICO Score vs Interest Rate over a specified time period
* Interest rates across the major demographics
