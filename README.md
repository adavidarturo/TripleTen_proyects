# Data Analytics Portfolio

## David Anampa

Portfolio of data analytics projects focused on transforming raw business data into reliable insights, measurable performance indicators, and actionable recommendations for stakeholders.

The projects demonstrate an end-to-end analytical workflow:

- Data exploration and quality assessment
- Data cleaning and preparation
- Feature engineering and aggregation
- Exploratory and statistical analysis
- SQL querying and business intelligence
- Hypothesis testing
- Data visualization
- Executive communication and recommendations

---

## Portfolio Overview

| Project                                  | Main Focus                                                                     | Key Technologies                              |
| ---------------------------------------- | ------------------------------------------------------------------------------ | --------------------------------------------- |
| 1. Urban Mobility & Economic Performance | Traffic and socioeconomic analysis across Latin American cities                | Python, Pandas, Matplotlib, Seaborn           |
| 2. ConnectaTel Customer Segmentation     | Customer behavior analysis and usage-based segmentation                        | Python, Pandas, Seaborn                       |
| 3. NovaRetail+ Revenue Analysis          | Correlation between customer behavior and annual revenue                       | Python, SciPy, Statistical Analysis           |
| 4. Landing Page A/B Test                 | Conversion, revenue, and marketing performance evaluation                      | Python, Hypothesis Testing, SciPy             |
| 5. RappiPlus Business Analytics          | End-to-end profitability, funnel, retention, experimentation, and BI reporting | Python, SQL, PostgreSQL, Statistics, Power BI |

---

# Featured Project

## 5. RappiPlus: From Data to Business Decisions

This is the most comprehensive project in the portfolio. It integrates data preparation, business analysis, SQL, statistical testing, and dashboard development into a complete decision-support workflow.

### Business Objective

Evaluate the performance of RappiPlus and translate operational data into recommendations related to:

- Revenue and profitability
- Product and order performance
- Marketing investment
- Conversion funnel drop-off
- Customer retention
- Checkout experience optimization

### Analytical Workflow

1. Validated and cleaned orders, catalog, and marketing datasets.
2. Removed duplicates, invalid records, and inconsistent values.
3. Calculated revenue, product cost, marketing investment, profit, average ticket, and sales KPIs.
4. Used SQL to analyze the conversion funnel and identify critical drop-off stages.
5. Built cohort retention analysis based on user registration and activity.
6. Evaluated a checkout UI experiment using a two-sample z-test for proportions.
7. Prepared executive-ready outputs for Power BI reporting.

### Key Deliverables

- Cleaned datasets prepared for reporting
- Profitability and sales KPIs
- SQL conversion funnel
- Cohort retention analysis
- Statistical evaluation of a checkout experiment
- Power BI executive dashboard and drill-through analysis

### Business Value

The project demonstrates how an analyst can move from raw operational data to business decisions. It connects financial performance, customer behavior, product analytics, experimentation, and visualization within one coherent framework.

[View the RappiPlus Dashboard](https://drive.google.com/drive/folders/1e7yHwJm8YKVyv2h-VxgedjDrMTvxgFXj?usp=drive_link)

---

# Other Projects

## 1. Urban Mobility & Economic Performance Analysis

This project analyzes the relationship between traffic congestion and economic indicators across major Latin American cities.

### Main Activities

- Standardized traffic and economic datasets
- Converted date and numeric fields
- Filtered and aggregated traffic observations by city and year
- Integrated mobility and economic indicators
- Created visualizations for congestion and GDP comparisons
- Exported a cleaned analytical dataset

### Main Finding

GDP per capita alone does not explain congestion levels. Traffic conditions vary considerably across cities, suggesting that urban structure, population density, infrastructure, and transportation systems also play important roles.

### Skills Demonstrated

Python, Pandas, data cleaning, aggregation, dataset integration, exploratory visualization, and business interpretation.

---

## 2. ConnectaTel Customer Behavior & Segmentation

This project analyzes telecommunications customer activity to identify usage patterns and potential customer segments.

### Main Activities

- Assessed missing values and invalid sentinel values
- Corrected invalid ages and unknown city values
- Converted date fields
- Aggregated calls, messages, and call minutes by customer
- Identified and evaluated behavioral outliers
- Created usage and age segments
- Developed customer-oriented recommendations

### Main Finding

Customers with higher usage represent potential opportunities for premium plans and targeted retention initiatives, while low-usage customers may benefit from promotional strategies designed to increase engagement.

### Skills Demonstrated

Data quality assessment, missing-value treatment, feature engineering, customer profiling, segmentation, outlier analysis, and business recommendations.

---

## 3. NovaRetail+ Customer Behavior & Revenue Analysis

This project investigates which customer behavior variables are most strongly associated with annual revenue.

### Main Activities

- Standardized and translated column names
- Classified variables as numeric, binary, or categorical
- Created correlation matrices and visualizations
- Applied Pearson and Spearman correlations
- Used point-biserial correlation for binary variables
- Applied Cramér's V to categorical relationships
- Interpreted results without confusing correlation with causation

### Main Findings

- Monthly purchases have a very strong association with annual revenue.
- Monthly visits show moderate associations with purchases and revenue.
- Premium membership and churn have weak or negligible relationships with annual revenue.
- Region and device type show little relevant association with customer behavior.

### Skills Demonstrated

Statistical analysis, correlation methodology, variable classification, visualization, non-causal interpretation, and analytical limitations.

---

## 4. Landing Page A/B Test Analysis

This project evaluates two landing page versions to determine which performs better in terms of conversion and average spend.

### Main Activities

- Validated experiment structure and data quality
- Standardized columns and converted date fields
- Compared average spend between page versions
- Applied Levene's test and Welch's t-test
- Compared conversion rates using a two-proportion z-test
- Evaluated traffic source and user type using chi-square tests
- Created conversion visualizations for stakeholders

### Main Findings

- Version B achieved a higher conversion rate than version A.
- Version B also generated higher average spend among converted users.
- Traffic source showed a statistically significant association with conversion, although the differences between channels were modest.
- User type did not show a statistically significant relationship with conversion.

### Skills Demonstrated

A/B testing, hypothesis formulation, statistical testing, conversion analysis, experiment interpretation, and business communication.

---

# Technical Skills

## Data Analysis

- Python
- Pandas
- NumPy
- Data cleaning and validation
- Feature engineering
- Aggregation and exploratory analysis

## Statistics

- Pearson correlation
- Spearman correlation
- Point-biserial correlation
- Cramér's V
- Levene's test
- Welch's t-test
- Two-proportion z-test
- Chi-square tests
- A/B test interpretation

## SQL and Databases

- PostgreSQL
- Common table expressions
- Window functions
- Conversion funnels
- Cohort retention analysis
- Aggregations and joins

## Visualization and Reporting

- Matplotlib
- Seaborn
- Power BI
- KPI design
- Executive dashboards
- Business-oriented storytelling

---

# Professional Approach

Across these projects, the analytical process follows a consistent structure:

1. Understand the business question.
2. Validate the quality and structure of the data.
3. Clean and transform the datasets appropriately.
4. Select analytical methods based on the data and objective.
5. Identify meaningful patterns and limitations.
6. Translate findings into business recommendations.
7. Communicate results through clear visual and executive-ready outputs.

The portfolio reflects a progression from exploratory data analysis to more advanced business analytics involving statistical testing, SQL-based product analysis, retention measurement, experimentation, and dashboard development.

---

# Repository Structure

```text
1st_project_py/
2nd_project_py/
3th_project_py/
4th_project_py/
5th_project/
README.md
```

## Note

Before publishing this repository publicly, database credentials and other sensitive connection details must be removed from notebooks and replaced with secure environment variables.
