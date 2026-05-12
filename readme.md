# Global E-Commerce Sales Analysis

## Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on a global e-commerce sales dataset.  
The goal is to understand sales performance, profit trends, customer behavior, and regional distribution using Python data analysis and visualization tools.

---

## Dataset Description
The dataset contains global e-commerce transaction records with features such as:
- Order details (Order Date, Quantity, etc.)
- Customer information (Country, Coutomer_Segment, etc.)
- Product details (Product_Category)
- Financial metrics (Sales, Profit, Discount, etc.)

---

## Tools & Libraries Used
- Python 
- Pandas 
- Matplotlib 
- Seaborn 

---

## Project Workflow

### 1. Data Loading & Inspection
- Loaded dataset using `pandas`
- Checked structure using:
  - `head()`
  - `info()`
  - `shape`

---

### 2. Data Cleaning & Wrangling
- Renamed columns for better readability
- Converted `Order_Date` to datetime format
- Checked for missing values and duplicates
- Created new feature: `Loss_Flag`

---

### 3. Exploratory Data Analysis (EDA)
- Analyzed categorical and numerical columns
- Used:
  - `value_counts()`
  - `unique()`
  - `describe()`

---

### 4. Aggregated Analysis
Performed group-based analysis:
- Total Sales by Product Category
- Total Sales by Region
- Profit by Category
- Discount vs Profit relationship

---

### 5. Filtering & Insights
- High sales transactions
- Low sales analysis
- Loss-making transactions
- Country-specific analysis

---

### 6. Loss Analysis
- Identified loss-making transactions
- Grouped losses by:
  - Product Category
  - Region

---

## Data Visualizations 

### 1. Sales Distribution
- Histogram to understand distribution and outliers

### 2. Category Comparison
- Bar charts for comparing sales across categories

### 3. Sales vs Profit Analysis
- Combined bar chart showing:
  - Sales
  - Profit
- Compared across product categories

---

## Key Insights
- Some product categories generate high sales but low profit
- Certain regions contribute more to overall revenue
- Loss-making transactions are concentrated in specific categories
- Discounts have a direct impact on profitability

---

## Project Outcome
This analysis helps in:
- Understanding business performance
- Identifying profitable and loss-making segments


---

## How to Run the Project

pip install pandas matplotlib seaborn

python analysis.py

