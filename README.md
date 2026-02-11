# Post-Covid-World-Layoffs

## Overview

Real-world datasets are rarely analysis-ready. In this project, I cleaned and standardized a global layoffs dataset using MySQL to transform messy, inconsistent raw data into a reliable, analysis-ready table. The goal was to simulate a common business scenario:
Prepare HR/financial workforce data so leadership can trust reporting and make informed decisions.

## Business Objective

Before companies can analyze workforce trends (layoffs by industry, country, or time), the underlying data must be:

**Accurate**

**Consistent**

**Properly formatted**

**Ethically handled**

This project focuses on building that trustworthy foundation.

## Business Questions
After cleaning, the dataset can reliably answer questions such as:

- Which industries experienced the most layoffs?

- Which countries were most impacted?

- How did layoffs trend over time (monthly/yearly)?

- Which companies had the largest single layoff events?

- Are there patterns tied to market sectors (e.g., Crypto vs Tech vs Retail)?

Without proper cleaning, these answers would be misleading due to duplicates, inconsistent labels, and missing values.

## Tools Used

MySQL

SQL (CTEs, filtering, grouping, transformations)

Data cleaning best practices

Data Cleaning Process
1. Created a working copy

Preserved the raw dataset for auditability and reproducibility

2. Removed duplicates

Eliminated repeated records to prevent inflated counts

3. Standardized categorical values

Examples:

Multiple variations of "Crypto" → standardized to Crypto

Country inconsistencies (e.g., "United States", "United States.") → unified

4. Fixed data types

Converted text dates → proper DATE format for time-series analysis

5. Handled null and blank values

Removed or corrected invalid rows where appropriate

Left unknown values as NULL rather than fabricating data (ethical integrity)

6. Removed unnecessary columns/rows

Simplified dataset for cleaner downstream analysis

## Outcome

Cleaned data through SQL, both to show the capabilities of SQL and my proficiency.

This makes the dataset reliable for SQL queries, reporting, and visualization tools like Power BI or Tableau.

## Key Skills Demonstrated

Data cleaning & wrangling

SQL transformations

Data validation

Handling messy real-world data

Ethical decision-making (no artificial data imputation)

Preparing datasets for analytics & BI tools
