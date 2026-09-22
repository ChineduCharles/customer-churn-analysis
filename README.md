# Customer Churn Analysis

## About the Project

This project analyzes customer churn using a fictional telecommunications dataset.

I approached the project with a simple question: **Why are customers leaving, and are there particular customer groups where churn is more common?**

Using Microsoft Excel, I cleaned and explored the data, created customer segments, investigated churn reasons and patterns, and developed a dashboard to communicate the key findings.

## Business Problem

Knowing that customers are leaving is not enough to make a good business decision. The company also needs to understand **why they are leaving and which groups are most affected**.

My analysis focused on:

- Measuring the overall churn rate.
- Identifying the major reasons for churn.
- Understanding the main churn categories.
- Comparing churn across customer demographics and age groups.
- Investigating patterns across customer plans and data consumption.

## Dataset

The dataset contains customer demographic, account, service usage, and churn information.

After preparing the data:

- **Total Customers:** 6,687
- **Churned Customers:** 1,796
- **Overall Churn Rate:** 26.86%

## Tools & Techniques

The project was completed entirely in **Microsoft Excel**.

I used:

- PivotTables
- PivotCharts
- Calculated Fields
- IFS statements
- COUNTIF
- Conditional Formatting
- Grouping

## My Approach

I started by defining the problem and identifying the questions I wanted the analysis to answer.

I then explored and prepared the data by checking for duplicates and records without useful customer attributes. I also created new categories to make the analysis more meaningful, including demographic groups, 10-year age groups, and broader churn-reason categories.

After preparing the data, I used PivotTables and calculated fields to investigate churn across different customer segments before presenting the main results in an Excel dashboard.

## Dashboard
## Dashboard

The dashboard provides an overview of customer churn, highlighting churn reasons, customer demographics, age groups, service usage, and plan-related patterns.

![Customer Churn Analysis Dashboard](images/customer_churn_dashboard.png)


## Key Findings

- The overall customer churn rate was approximately **26.86%**, representing 1,796 churned customers.

- **Competitor-related reasons** accounted for the largest churn category.

- **"Competitor made better offer"** was the leading individual churn reason, closely followed by **"Competitor had better devices."**

- Senior customers recorded a churn rate of approximately **38.22%**, despite representing a relatively small proportion of the customer base.

- Customers aged **19–28** had a relatively low churn rate of approximately **21.96%**, while also representing a large customer segment.

- Churn also varied across customer plans, data consumption levels, demographics, and other customer characteristics.

## Recommendations

Based on the patterns identified:

- The company should review the competitiveness of its offers and device options, since competitor-related factors account for a large share of churn.

- The high churn rate among senior customers deserves further investigation to understand the specific reasons customers in this group are leaving.

- Retention efforts should consider differences between customer segments rather than relying only on the company's overall churn rate.

- Large customer segments with relatively low churn should still be monitored because even a small increase in their churn rate could affect a significant number of customers.

## Limitations

This project uses a fictional dataset, so the findings should be treated as a portfolio case study rather than conclusions about a real telecommunications company.

The analysis identifies patterns and associations in the available data. These patterns do not, on their own, establish that a particular customer characteristic causes churn.

## Repository Contents

- `customer_churn_analysis.xlsx` — Complete Excel analysis and dashboard
- `images/` — Dashboard image and project visuals
- `README.md` — Project documentation

---
## Author

**Chukwu Chinedu Charles**  
B.Sc. Statistics | Junior Data Analyst
