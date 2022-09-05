# Prosper Loan Data Exploration
## by Isiaq Adebayo Okeyode


## Dataset

> The dataset consists of information 114,000 rows of loan data, and 81 variables including Loan amount, Stated Monthly Income, DebtToIncomeRatio, Loan Term, Prosper Score and many others.

## Data Wrangling

> I started by importing all the packages needed for the project e.g Numpy, Pandas, Matplotlib, and Seaborn.

> I read in the data using pandas.read_csv.

> I assessed the data by checking the shape, the datatypes and so on.

> I subset the data to pick out only the variables needed for the analysis.

> I cleaned the data by dropping null rows, changing datatypes, replacing some categorical variables value.

> I performed Univariate, Bivariate, and Multivariate analysis on the cleaned data.

## Summary of Findings

> In the analysis, I found out that Positive correlation exist between Loan Amount and Borrower's Monthly Income. I discovered that with borrowers with a relatively low Monthly Income, the probabilities of getting a Low or High Loan Amount is low. However, with a High Monthly Income, the possibility is High.

> A strong relationship exists between the Monthly Payments and the Loan amount with modifying effect from the Loan Term. On encoding a bivariate plot, with a third variable Loan Term, the Visualization shows that Borrowers with longer Loan Term (36 or 60 months) receives larger Loan amounts.

> I also discovered that relationship exist between Loan Amount and the categorical variables. More Loans are associated with Borrowers with a Longer loan Term, Low risk involved (high Prosper Score), Owning a Home and being successfully employed.


## Key Insights for Presentation

> For the presentation, I focused more on the influence of the  Monthly Loan Payment, Stated Monthly Income), Loan Term, DebtToIncomeRatio on Loan Amount. I started by plotting the Loan Amount distribution, followed by other variables, then I plot scatter plots showing correlations.

> Scatter plots showing the correlation between Loan Amount and Predictor variable, Stated Monthly income was plotted. The plot showed that When a borrower has relatively low Monthly Income (<8,000 dollars) the probabilities of getting low and high Loan Amount are similar. However, when the borrower’s Monthly Income is high (>8,000 dollars), he/she is more likely to get a Large Loan Amount.

> Then, I plotted scatter and point plots showing correlations of 3 or more variables, to show that Loan Term plays a part in determining the amount of loan to be given out. It is also influenced by the Prosper score (risk score).That is, The Longer the Loan Term, and the better the risk score(Prosper Score), the larger the Loan Amount to be given out. This could be because Lenders are more open to giving out loans to borrowers who they don't assess as risks(for defaulting), and providing a long term to pay back the large Loan amount as an assurance.