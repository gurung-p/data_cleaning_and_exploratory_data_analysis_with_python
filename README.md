## Sales Performance Analysis
A data analytics project exploring regional, product, and category‑level sales trends using **Python, Pandas, Matplotlib, and Seaborn.**

## Project Overview
This project explores a **sales dataset** containing transaction records from **January to April 2024** across multiple regions, product types, and categories. **The raw data initially included inconsistencies, formatting issues, and duplicated values**, which were **cleaned and standardised** to create a reliable foundation for analysis. After preparing the dataset, the project applies **visual exploratory data analysis (EDA) to uncover patterns in sales performance, profit margins, and product demand**. The findings highlight regional differences, product‑level trends, and time‑based sales behaviour, offering insights that can **support reporting, forecasting, and strategic decision‑making.**

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
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

## Exploratory Data Analysis (EDA)
1. **Total Sales by Region:**
A bar chart summarising which regions generated the highest total sales.
<img width="600" height="466" alt="image" src="https://github.com/user-attachments/assets/c077996a-bde5-4bb0-a10b-2bf705a8acf1" />

2. **Total Sales by Product:**
Comparison of product performance across all transactions.
<img width="569" height="396" alt="image" src="https://github.com/user-attachments/assets/948eda2c-98e8-462e-82f2-887a92ba79ba" />

3. **Sales by Category:**
A pie chart showing the share of sales between Electronics and Gadgets.
<img width="458" height="410" alt="image" src="https://github.com/user-attachments/assets/a637bfd1-5ea7-4944-b256-d92de8c7dce0" />

4. **Monthly Sales Trend:**
Time‑series analysis of total sales from January to April 2024.
6. **Daily Sales Trend:**
Line plot showing fluctuations in daily sales.
7. **Profit Margin Distribution:**
Histogram + KDE curve showing how profit margins vary across products.
8. **Units Sold vs Total Sales:**
Scatterplot illustrating the relationship between units sold and revenue, colored by category.

## Key Insights
- **North and South** regions show the strongest sales performance.
- **Tablets and Laptops** dominate total sales across the dataset.
- **Electronics** account for the majority of revenue.
- **Sales** show a **steady upward trend** from January to April.
- **Profit margins cluster between 8-15%**, with some products consistently outperforming others.
- **Higher units sold** generally correlate with higher revenue, especially in the Gadgets category.
