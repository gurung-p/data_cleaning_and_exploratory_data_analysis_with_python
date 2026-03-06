## Sales Performance Analysis (2024)
A data analytics project exploring regional, product, and category‑level sales trends using Python, Pandas, Matplotlib, and Seaborn.

## Project Overview
This project explores a sales dataset containing transaction records from January to April 2024 across multiple regions, product types, and categories. The raw data initially included inconsistencies, formatting issues, and duplicated values, which were cleaned and standardised to create a reliable foundation for analysis. After preparing the dataset, the project applies visual exploratory data analysis (EDA) to uncover patterns in sales performance, profit margins, and product demand. The findings highlight regional differences, product‑level trends, and time‑based sales behaviour, offering insights that can support reporting, forecasting, and strategic decision‑making.

### Dataset Summary Table
The dataset includes the following fields:

|**Field**             | **Description** |
|----------------------|-----------------|
| **Date**             | Transaction date |
| **Region**           | Geographic sales region: North, South, East, West |
| **Product**          | Item sold: Laptop, Tablet, Phone, Desktop, Monitor |
| **Category**         | Product classification: Electronics, Gadgets |
| **Units Sold**       | Number of units sold in the transaction |
| **Unit Price**       | Selling price per individual unit |
| **Total Sales**      | Total revenue from the transaction (Units Sold × Unit Price) |
| **Profit Margin (%)**| Percentage of revenue retained as profit after costs |

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Exploratory Data Analysis (EDA)
1. **Total Sales by Region:**
A bar chart summarizing which regions generated the highest total sales.
2. **Total Sales by Product:**
Comparison of product performance across all transactions.
3. **Sales by Category:**
A pie chart showing the share of sales between Electronics and Gadgets.
4. **Monthly Sales Trend:**
Time‑series analysis of total sales from January to April 2024.
5. **Daily Sales Trend:**
Line plot showing fluctuations in daily sales.
6. **Profit Margin Distribution:**
Histogram + KDE curve showing how profit margins vary across products.
7. **Units Sold vs Total Sales:**
Scatterplot illustrating the relationship between units sold and revenue, colored by category.

## Key Insights
- North and South regions show the strongest sales performance.
- Tablets and Laptops dominate total sales across the dataset.
- Electronics account for the majority of revenue.
- Sales show a steady upward trend from January to April.
- Profit margins cluster between 8-15%, with some products consistently outperforming others.
- Higher units sold generally correlate with higher revenue, especially in the Gadgets category.
