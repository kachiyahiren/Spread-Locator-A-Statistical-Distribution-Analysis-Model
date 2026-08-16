# Spread Locator: A Statistical Distribution Analysis Model

## Overview

Spread Locator is a statistical analysis project based on an e-commerce transaction dataset. The project applies probability distributions, statistical transformations and visualization techniques to understand transaction behavior.

## Objective

The objective of this project is to:

- Analyze transaction success and failure.
- Model transaction counts using probability distributions.
- Analyze transaction amount distributions.
- Test normality using Q-Q plots.
- Apply Box-Cox transformation.
- Calculate Z-scores and probabilities.
- Compare Log-Normal and Power Law models.
- Interpret statistical findings for business decision-making.

## Dataset

The dataset contains 220 transaction records and 7 variables:

- transaction_id
- customer_id
- transaction_amount
- transaction_date
- transaction_count
- region
- transaction_status

## Statistical Techniques

The following techniques were applied:

1. Bernoulli Distribution
2. Binomial Distribution
3. Poisson Distribution
4. Log-Normal Distribution
5. Power Law / Pareto Distribution
6. Q-Q Plot
7. Shapiro-Wilk Normality Test
8. Box-Cox Transformation
9. Z-score
10. Probability Density Function
11. Cumulative Distribution Function
12. AIC-based model comparison

## Key Findings

- The success rate is approximately 44.55%.
- The failure rate is approximately 55.45%.
- Average daily transactions are approximately 7.10.
- Probability of exactly 10 daily transactions under the Poisson model is approximately 7.39%.
- Transaction amounts are strongly right-skewed.
- Transaction amounts do not follow a normal distribution.
- Box-Cox transformation substantially reduces skewness.
- Log-Normal provides a better fit than the tested Power Law/Pareto model.
- The actual proportion of transactions above ₹5000 is approximately 11.36%.

## Tools and Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Excel

## Project Files

- `spread_locator_analysis.ipynb` — Complete Python analysis
- `spread_locator_dataset.xlsx` — Dataset


## Conclusion

The analysis shows that transaction amounts are strongly right-skewed and are better represented by a Log-Normal model than a Normal distribution. Statistical distributions and transformations provide useful insights into transaction frequency, transaction amounts and unusual transaction behavior.
