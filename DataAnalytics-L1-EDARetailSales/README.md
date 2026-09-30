# EDA on Retail Sales Data

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to identify sales trends, customer demographics, product performance, and relationships between numerical variables.

The analysis was completed as part of the OASIS INFOBYTE Data Analytics Internship.

## Objective

The main objective of this project is to analyze retail sales data and uncover meaningful patterns, customer behavior trends, and actionable business insights using Python.

## Dataset

The dataset contains 1,000 retail transactions and 9 columns:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

The dataset was inspected for missing values, duplicate records, data types, and basic statistical information.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Analysis Performed

### 1. Data Inspection

Performed:

- Dataset shape analysis
- Column and data type inspection
- Missing value analysis
- Duplicate record detection

### 2. Descriptive Statistics

Calculated:

- Mean
- Median
- Mode
- Standard Deviation
- Summary statistics for numerical variables

### 3. Sales Trend Analysis

Analyzed:

- Monthly sales trends
- Quarterly sales trends

Line charts were used to identify changes in sales over time.

### 4. Customer Demographics

Analyzed:

- Customer gender distribution
- Customer age groups

The 46-55 age group had the highest representation with 229 customers (22.9%).

### 5. Product Analysis

Analyzed:

- Quantity sold by product category
- Revenue by product category

Clothing recorded the highest quantity sold with 894 units, while Electronics generated the highest revenue at 155,905.

### 6. Correlation Analysis

A correlation matrix and heatmap were created to understand relationships between numerical variables.

Key findings:

- Price per Unit has a strong positive correlation with Total Amount (0.85).
- Quantity has a moderate positive correlation with Total Amount (0.37).

### 7. Additional Analysis

Sales were also analyzed by gender.

- Female customers generated total sales of 232,840.
- Male customers generated total sales of 223,160.

Female customers generated slightly higher total sales in this dataset.

## Key Insights

1. The dataset contains 1,000 transactions and 9 columns.
2. There are no missing values or duplicate records.
3. Monthly sales fluctuate throughout the year.
4. Q4 2023 recorded the highest sales among the complete quarters.
5. Customer gender distribution is nearly balanced, with 510 female and 490 male records.
6. The 46-55 age group has the highest representation with 229 customers (22.9%).
7. Clothing has the highest quantity sold with 894 units.
8. Electronics generates the highest revenue with 155,905.
9. Price per Unit has a strong positive relationship with Total Amount.
10. Female customers generated slightly higher total sales than male customers.

## Business Recommendations

1. **Focus on high-revenue product categories:** Electronics generated the highest revenue. The business can maintain adequate inventory and use targeted promotions for high-performing products.

2. **Improve seasonal planning:** Monthly and quarterly sales show variations. Historical sales patterns can be used for inventory planning and promotional campaign scheduling.

3. **Target key customer age groups:** The 46-55 age group is the largest customer segment. Marketing campaigns can be designed to better understand and serve this customer segment.

4. **Monitor pricing and product mix:** Price per Unit has a strong positive relationship with Total Amount. Pricing and product mix can be monitored when planning revenue-growth strategies.

## Conclusion

The exploratory data analysis provided insights into sales trends, customer demographics, product categories, and relationships between numerical variables.

The analysis identified monthly and quarterly sales patterns, a balanced gender distribution, the largest customer age group, category-level sales performance, and strong relationships between price per unit and total sales amount.

These findings can support data-driven decisions related to inventory planning, customer targeting, pricing, and promotional activities.

## Project Structure

```text
DataAnalytics-L1-EDARetailSales/
│
├── EDA_Retail_Sales.ipynb
├── retail_sales.csv
├── README.md
└── screenshots/

## Author

**Vinay Tehare**

Data Analytics Intern | BCA Graduate

- LinkedIn: https://www.linkedin.com/in/vinay-tehare/
- GitHub: https://github.com/tehare-vinay
- Email: vinaytehare@gmail.com

## Internship

**OASIS INFOBYTE — Data Analytics Internship**

- Track: Data Analytics
- Level: Level 1
- Task: Task 1 — EDA on Retail Sales Data
