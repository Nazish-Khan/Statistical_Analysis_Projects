Summary of Statistical Methods Used
In the project titled "Descriptive Analysis of E-book Sales of a Publishing Company," various statistical methods were employed to analyze the e-book sales data. The analysis focused on understanding the relationship between e-book sales and factors such as average review scores, total number of reviews, sale price, and genre. Below is a summary of the statistical methods used in the analysis:

Descriptive Statistics

Summary Statistics:
Used to provide an overview of the dataset, including measures of central tendency (mean, median) and dispersion (standard deviation, range).

Data Visualization:
Histograms and boxplots were used to visualize the distribution of daily sales, sale price, average review, and total reviews.
Scatter plots with regression lines and density plots were used to explore relationships between variables.

Inferential Statistics

Correlation Analysis:
Pearson correlation coefficients were calculated to assess the strength and direction of linear relationships between numeric variables (e.g., daily sales, average review, total reviews, sale price).

One-Sample T-Test:
Conducted on daily sales to determine if the sample mean significantly differs from a hypothesized population mean (zero in this case).

Confidence Intervals:
Confidence intervals were calculated for the mean of daily sales to estimate the range within which the true population mean lies with a certain level of confidence (95%).

Regression Analysis

Simple Linear Regression:
Assessed the impact of single predictors such as average review and total reviews on daily sales.
Example: lm(daily.sales ~ avg.review)

Multiple Linear Regression:
Evaluated the combined effect of multiple predictors on daily sales.
Example: lm(daily.sales ~ avg.review * total.reviews)

Analysis of Variance (ANOVA):
Used to compare the baseline model (only intercept) with models including predictors like average review and total reviews.
Example: anova(m.sales.baseline, m1)

Model Diagnostics

Model Comparison:
Compared different regression models to determine the best fit for predicting daily sales.
Example: anova(m1, m2)

Interaction Effects:
Investigated the interaction between sale price and genre to understand their combined impact on daily sales.
Example: lm(daily.sales ~ sale.price * genre)

Multicollinearity Check:
Variance Inflation Factor (VIF) was used to check for multicollinearity among predictors in the regression models.


Key Findings

Average Review: Showed a non-significant relationship with daily sales, both with and without outliers.
Total Reviews: Exhibited a strong positive correlation with daily sales, indicating that more reviews generally lead to higher sales.
Sale Price: Had a significant negative effect on daily sales, suggesting that higher prices lead to fewer sales.
Genre: Significantly impacted daily sales, with variations observed across different genres (e.g., non-fiction vs. YA fiction).

Conclusion
The statistical analysis provided insights into how various factors influence e-book sales. While average review scores alone were not strong predictors of sales, the total number of reviews and sale price had significant effects. Additionally, genre played a crucial role in sales performance, highlighting the importance of considering multiple factors in strategic decision-making for the publishing company.






