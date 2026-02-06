Loan Repayment Analysis – Exploratory Data Analysis (EDA)

Project Overview :

This project focuses on Exploratory Data Analysis (EDA) of a loan dataset to understand borrower behavior and identify key factors influencing loan repayment outcomes. The analysis aims to uncover patterns, trends, and risk indicators that can help financial institutions make better lending decisions.

The project does not include machine learning models and is purely focused on data understanding, visualization, and insights generation.

Objectives :

Understand the structure and quality of loan data

Analyze borrower financial and credit-related features

Identify factors affecting loan repayment behavior

Generate meaningful insights using visualizations

Dataset Information :

Source: Kaggle

Records: 9,578 loan entries

Target Variable: not.fully.paid

Features Include:

Interest Rate (int.rate)

FICO Score (fico)

Debt-to-Income Ratio (dti)

Loan Purpose (purpose)

Revolving Balance (revol.bal)

Credit History Length

Data Preparation & Transformation :

Checked and confirmed no missing values

Verified no duplicate records

Converted interest rates from decimal to percentage

Created a new feature for credit history in years

Removed redundant columns for better clarity

Exploratory Data Analysis Highlights :

Most loans fall within the 10%–14% interest rate range

Borrowers with higher FICO scores are more likely to fully repay loans

Higher DTI ratios are associated with loan defaults

Debt consolidation is the most common loan purpose

The dataset shows class imbalance, with more fully paid loans

Tools & Technologies :

Programming Language: Python (Latest)

Libraries Used:

pandas

numpy

matplotlib

seaborn

Key Insights :

Credit score and DTI are strong indicators of repayment behavior

Higher interest rates are generally linked to higher borrower risk

Clean and well-structured data supports reliable analysis


📌 Conclusion

This EDA project provides valuable insights into loan repayment patterns and borrower risk factors. The findings can support better decision-making and serve as a foundation for future predictive modeling projects.
