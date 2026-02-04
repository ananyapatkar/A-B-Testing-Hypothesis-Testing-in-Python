# A-B-Testing-Hypothesis-Testing-in-Python

## Overview
This project performs an A/B testing analysis on an e-commerce dataset to evaluate whether a new landing page leads to higher user conversion compared to an old landing page. Statistical hypothesis testing is used to make a data-driven business decision.

## Dataset Description
The analysis uses two datasets:
- **ab_data.csv**: Contains user-level experiment data including group assignment, landing page, and conversion outcome.
- **countries.csv**: Contains country information for each user (used for optional extended analysis).

Key columns used:
- `group`: Control or treatment
- `landing_page`: Old page or new page
- `converted`: 1 if the user converted, 0 otherwise
- 
## Objective
To determine whether the new landing page significantly improves conversion rates compared to the old landing page using statistical methods.

## Methodology
1. Data loading and inspection  
2. Data cleaning to remove mismatched group and page records  
3. Separation of control and treatment groups  
4. Definition of null and alternative hypotheses  
5. Calculation of conversion rates  
6. Two-sample t-test for hypothesis testing  
7. Confidence interval estimation  
8. Visualization of conversion rates  
9. Final business recommendation  

Significance level used: **α = 0.05**

## Tools and Libraries
- Python
- Google Colab
- pandas
- numpy
- scipy
- matplotlib

## Results Summary
- The difference in conversion rates between the old and new landing pages was analyzed.
- The p-value obtained was greater than 0.05.
- The 95% confidence interval for the difference included zero.

This indicates that the observed difference is **not statistically significant**.

