# Supplement Sales Analysis in Microsoft Excel

## Project Objective

The objective is to analyze supplement sales performance across products, locations, and sales platforms in order to identify revenue drivers, customer purchasing patterns, and opportunities to improve business performance.

## Dataset

View dataset https://www.kaggle.com/datasets/zahidmughal2343/supplement-sales-data 

The dataset contains transactional sales information with the following columns:

- Date
- Product Name
- Category
- Units Sold
- Price
- Revenue
- Discount
- Units Returned
- Location
- Platform

---


## Business Questions

### 1. Which product generates the highest net revenue?

### 2. How does net revenue change throughout the year?

### 3. Which sales platforms record the highest sales volume?

### 4. Which locations contribute the largest share of total net revenue?

---

## Project Workflow

1. Import raw dataset
2. Clean and validate the data
3. Perform exploratory analysis
4. Create PivotTables
5. Build interactive dashboard
6. Generate business insights
7. Provide recommendations


## Data Cleaning

Before performing the analysis, the dataset was cleaned and validated in Microsoft Excel to ensure the accuracy, consistency, and reliability of the results.

The following data cleaning steps were completed:

- Verified the dataset structure, confirming **4,384 records** and **10 original columns**.
- Confirmed that all column names were correctly labeled and that the data types were appropriate for each field.
- Checked for duplicate records and found **no duplicate transactions**.
- Inspected all columns for missing values.
- Identified **89 blank values** in the **Discount** column. Based on the dataset structure, these represented transactions with no discount applied and were replaced with **0**.
- Formatted the **Discount** column as a percentage to improve readability while preserving the underlying values.
- Validated the **Revenue** column by confirming that the recorded revenue matched the calculation **Units Sold × Price**, indicating that discounts were stored separately and were not deducted from the recorded revenue.
- Reviewed numeric fields for invalid values, including negative values, zero values, and other logical inconsistencies that could affect the analysis.
- Created additional calculated fields to support business analysis:
  - **Month** – for monthly sales trend analysis.
  - **Year** – to distinguish transactions across multiple years.
  - **Net Revenue** – to estimate revenue after applying discounts.
  - **Discount Amount** – to measure the monetary value of discounts given.
  - **Return Rate** – to evaluate the proportion of sold units that were returned.
- Saved the cleaned dataset as the analysis-ready version for dashboard development.

The cleaned dataset served as the foundation for all subsequent PivotTables, visualizations, and business insights presented in this project.