# Prosper Loan Data
## by Collins G. Kimotho


## Dataset

The [Prosper loan](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) dataset contains information on loans funded through the Prosper platform from November 2005 to March 2014. The dataset has 113,937 observations and 81 variables. Each observation represents a unique loan and the variables include loan characteristics such as loan amount, interest rate, loan status, borrower employment status, borrower income range, and credit ratings assigned by Prosper.

Before the exploration, data wrangling steps were performed on the dataset, including removing duplicate observations, removing columns with mostly missing data, and removing rows with missing data in the variables of interest. Additionally, some variables were transformed, including converting ProsperRating to an ordered categorical variable and creating a new variable for loan status with only two categories (completed and defaulted).

## Summary of Findings
Based on the analysis of the Prosper loan dataset, several insights were discovered.

Firstly, it was found that loans with a higher original amount tend to have longer terms and higher interest rates, but lower risk ratings. Borrowers with higher income tend to take out larger loans, but also tend to have lower interest rates and risk ratings.

Secondly, the loan status was found to be correlated with several factors, including income range, employment status, and debt-to-income ratio. For example, current loans tend to have higher income ranges and lower debt-to-income ratios, while charged-off loans tend to have lower income ranges and higher debt-to-income ratios.

Thirdly, it was found that loan status can have an impact on the relationship between other variables. For example, the relationship between Prosper rating and loan original amount varies across loan status categories, and the relationship between income range and loan original amount differs across loan status categories as well.

Overall, the analysis provides valuable insights for borrowers, lenders, and policymakers to better understand the factors that impact loan outcomes and inform decision-making.



## Key Insights for Presentation

One main thread from my exploration is the relationship between loan amount and borrower APR across different loan statuses and borrower employment statuses. I will focus on creating visualizations that effectively communicate this relationship.

For my presentation, I will make some design changes from my exploration step to better highlight the main thread. I will use larger font sizes for titles and labels, and I will simplify the color schemes to make the visualizations more accessible. I will also use consistent axis limits across visualizations to aid comparison. Additionally, I will provide more context and explanation for each visualization in the form of annotations and captions.

