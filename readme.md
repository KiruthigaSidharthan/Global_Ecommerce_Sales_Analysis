# E-Commerce Sales Transaction Analysis

## Project Overview

This project analyzes e-commerce sales transaction data to understand sales performance, customer purchasing behavior, product trends, profitability and operational factors.

The project combines data cleaning, data transformation, SQL analysis and data visualization to transform raw transaction data into meaningful business insights.

Two datasets were analyzed:

- **Global E-Commerce Sales Dataset**: Contains order details, customer information, product information, sales, discounts, shipping costs and profit data.
- **E-Commerce sales Transaction Dataset**: Contains transaction details, customer demographics, product information, delivery time, returns, and profit margin data.

The goal of this project is to identify factors affecting sales performance and provide insights that can support data-driven business decisions.

The main objectives of this project are:

- Analyze sales and profit performance across product categories.
- Identify top-performing countries and customers based on sales.
- Understand customer and transaction patterns.
- Analyze product profitability.
- Explore the impact of pricing and discounts on sales performance.
- Create visual insights to support business recommendations.

---

## Tools and Technologies

- Python
  - Pandas
  - NumPy
  - Matplotlib
- SQL / SQLite
- Jupyter Notebook
- Git & GitHub

---

## Data Preparation

The following data preparation steps were performed:

- Loaded and explored both datasets.
- Reviewed dataset structure, columns, missing values, and duplicates.
- Standardized column names across datasets.
- Converted date columns into datetime format.
- Standardized categorical values such as payment methods.
- Checked for invalid numerical values.
- Created additional features:
  - `order_year`
  - `order_month`
  - `order_day`
  - `discount_amount`
  - `loss_flag`

---

## Database Design

Cleaned data was stored in a SQLite database with the following tables:

- `global_products`
- `global_sales`
- `customers`
- `transaction_sales`
- `transaction_products`

These tables were used for SQL-based analysis.

---

## SQL Analysis Performed

The project includes the following SQL analyses:

1. Total Sales and Profit by Product Category
2. Top 10 Countries by Sales
3. Average Profit Margin by Customer Gender
4. Average Delivery Time by Payment Method
5. Products with Above-Average Profit
6. Top 10 Customers by Total Sales
7. Most Frequently Ordered Products

---

## Visualizations

The following visualizations were created:

### 1. Total Sales by Product Category
- Bar chart showing revenue contribution from each category.

### 2. Top 10 Countries by Sales
- Horizontal bar chart comparing sales performance across countries.

### 3. Price vs Profit Relationship
- Scatter plot analyzing the relationship between product price and profit.

### 4. Top 10 Customers by Total Sales
- Line chart showing customers contributing the highest sales.

### 5. Most Frequently Ordered Products
- Pie chart showing products with the highest order quantities.

---

## Key Insights

- Product categories showed different levels of sales contribution, helping identify high-performing areas.
- Country-level analysis highlighted regions generating the most revenue.
- Customer sales analysis identified valuable customers contributing significantly to total sales.
- Profit analysis helped identify profitable and loss-making transactions.
- Discount and pricing analysis provided insights into factors affecting profitability.

---

## Conclusion

This project demonstrates how Python, SQL, and visualization techniques can be combined to clean, analyze and communicate insights from e-commerce data. The findings can help businesses improve sales strategies, understand customer behavior and make informed decisions.

---


