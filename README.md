# Prosper Loan Data Exploration

## Dataset

The dataset consists of information 114,000 rows of loan data, and 81 variables including Loan amount, Stated Monthly Income, DebtToIncomeRatio, Loan Term, Prosper Score and many others.

## Data Wrangling

Commencing the project, I imported essential packages such as Numpy, Pandas, Matplotlib, and Seaborn. Subsequently, I used pandas.read_csv to read in the data. A thorough assessment of the data followed, encompassing examinations of its shape, data types, and other relevant attributes.
To streamline the dataset for analysis, I subselected only the necessary variables. The data cleaning phase involved the removal of null rows, adjustments to data types, and the replacement of certain categorical variable values.
With the refined dataset, I proceeded to conduct comprehensive analyses, including Univariate, Bivariate, and Multivariate analyses.

## Summary of Findings

During the analysis, it was evident that a positive correlation exists between Loan Amount and Borrower's Monthly Income. Notably, borrowers with relatively low Monthly Income had lower probabilities of obtaining either Low or High Loan Amounts. Conversely, individuals with a high Monthly Income exhibited a higher likelihood of securing a High Loan Amount.
Furthermore, a robust relationship was identified between Monthly Payments and Loan Amount, with a modifying effect from the Loan Term. The bivariate plot, incorporating the third variable Loan Term, visually indicated that Borrowers with longer Loan Terms (36 or 60 months) tended to receive larger Loan amounts.
Additionally, the analysis revealed associations between Loan Amount and categorical variables. Borrowers with longer loan terms, lower risk (high Prosper Score), homeownership, and successful employment were correlated with a higher incidence 


## Key Insights found:

In the presentation, my emphasis centered on the impact of Monthly Loan Payment, Stated Monthly Income, Loan Term, and DebtToIncomeRatio on Loan Amount. I initiated the discussion by visualizing the distribution of Loan Amount, followed by exploring other relevant variables, and finally, I generated scatter plots to illustrate correlations.

A key observation emerged from the scatter plot illustrating the correlation between Loan Amount and the predictor variable Stated Monthly Income. This plot highlighted that borrowers with relatively low Monthly Income (<$8,000) had similar probabilities of obtaining both low and high Loan Amounts. Conversely, when a borrower's Monthly Income exceeded $8,000, there was a higher likelihood of securing a larger Loan Amount.

Subsequently, scatter and point plots were employed to reveal correlations involving three or more variables, emphasizing the influence of Loan Term and Prosper Score (risk score) on the Loan Amount. The visualizations conveyed that an extended Loan Term and a higher risk score (Prosper Score) were associated with larger Loan Amounts. This suggested that lenders might be more willing to extend loans to borrowers assessed as low risks, providing an extended period for repayment as a safeguard for larger Loan Amounts.
