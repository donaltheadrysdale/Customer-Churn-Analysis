# Bank Customer Churn Analysis

## Project Overview

This project analyzes bank customer data to investigate patterns associated with customer churn. Using Python, Pandas, and statistical analysis, the goal is to identify customer characteristics associated with leaving the bank and translate the findings into actionable business insights.

Customer churn is an important business concern because losing customers can affect revenue, customer retention, and long-term growth. Understanding which customer segments have higher churn rates can help businesses make more informed decisions about customer retention strategies.

## Business Problem

Banks need to understand which customers are most likely to leave and what characteristics are associated with churn.

This project investigates customer demographics, banking product usage, and other account characteristics to identify patterns in customer churn.

## Research Questions

The analysis focuses on the following questions:

1. Is customer churn associated with gender?
2. Do churn rates differ across age groups?
3. Is the number of bank products a customer owns associated with churn?
4. Do churn rates differ by geographic location?
5. Is credit card ownership associated with churn?
6. How does customer tenure relate to churn?
7. Are credit score groups associated with different churn rates?

These questions will be explored using descriptive statistics, data visualization, and appropriate statistical tests.

## Dataset

The project uses the Bank Customer Churn Modelling dataset, which contains customer-level information and a binary indicator of whether a customer exited the bank.

Relevant variables include:

- `Gender` — Customer gender
- `Age` — Customer age
- `CreditScore` — Customer credit score
- `Geography` — Customer's country
- `Tenure` — Number of years the customer has been with the bank
- `NumOfProducts` — Number of bank products held by the customer
- `HasCrCard` — Whether the customer has a credit card
- `Exited` — Whether the customer left the bank (1 = exited, 0 = retained)

The dataset contains 10,000 customer records in the version currently being analyzed.

## Tools & Technologies

- **Python** — Data analysis and statistical computing
- **Pandas** — Data cleaning, grouping, and transformation
- **SciPy** — Statistical hypothesis testing
- **Matplotlib / Seaborn** — Data visualization
- **Jupyter Notebook / Google Colab** — Analysis environment
- **Git & GitHub** — Version control and project documentation

## Project Workflow

### 1. Data Inspection and Cleaning
- Inspect dataset structure and data types.
- Check for missing values and duplicate records.
- Validate customer identifiers and key variables.
- Create categorical groups for age, credit score, tenure, and number of bank products.

### 2. Exploratory Data Analysis
- Calculate overall customer churn.
- Compare churn rates across customer segments.
- Examine demographic and account characteristics associated with churn.
- Identify patterns that warrant further investigation.

### 3. Statistical Analysis
- Formulate null and alternative hypotheses.
- Use chi-square tests to examine associations between churn and categorical variables.
- Interpret p-values alongside observed differences and effect sizes.
- Evaluate whether findings are statistically meaningful without assuming causation.

### 4. Business Insights and Recommendations
- Summarize the strongest patterns in customer churn.
- Identify customer segments that may warrant further investigation.
- Develop evidence-based recommendations, subject to the results of the analysis.

## Current Status

**In progress:** Data inspection, feature grouping, and exploratory data analysis.

Initial churn-rate comparisons have identified differences across gender, age groups, geography, and number of bank products. These patterns will be investigated further through statistical testing before conclusions are drawn.

## Limitations

- Observed associations do not establish causation.
- Results depend on the dataset's coverage and representativeness.
- Grouping continuous variables can obscure differences within categories.
- Statistical significance will be evaluated alongside practical importance and sample sizes.

## Future Improvements

- Complete statistical hypothesis testing.
- Explore multivariable logistic regression, if appropriate.
- Translate findings into practical customer retention recommendations.

## Key Takeaway

The goal of this project is to demonstrate how data analysis can help businesses investigate customer churn, evaluate patterns in customer behavior, and make more informed retention decisions.
