# Eniac Discount Strategy Analysis Project

## Overview

This project analyzes the discount strategies of Eniac, an e-commerce platform specializing in Apple-compatible accessories. Using transactional data from 2017-2018, we evaluate how discounts impact sales performance, inventory management, and customer behavior. The analysis provides actionable insights for optimizing promotional campaigns while maintaining profitability.

![Jupyter Notebook Badge](https://img.shields.io/badge/Made_with-Jupyter-orange?logo=Jupyter)
![Python Badge](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Pandas Badge](https://img.shields.io/badge/Analysis-Pandas-yellowgreen)

## Data Sources

The analysis combines multiple datasets from different sources:

- **Base datasets (CSV files)**:
  - `orders.csv` - contains order details including order ID, creation date, total paid, and order state.
  - `orderlines.csv` - details of products within orders, including product IDs, quantities, and unit prices.
  - `products.csv` - product information such as SKU, name, description, price, promotional price, stock availability, and product type.
  - `brands.csv` - brand information linked to products.

These datasets are combined programmatically within the Jupyter notebook to analyze the relationship between discounts and sales performance.

## Methodology

- **Data Cleaning & Preparation**:
  The raw data was cleaned to handle missing values, duplicates, and inconsistent formats. Data types were unified and datasets merged to create a comprehensive view of orders, products, and discounts.

- **Exploratory Data Analysis (EDA)**:
  Key metrics such as total sales, order counts, and discount rates were calculated. Visualizations were used to identify trends and patterns in sales relative to discounted and non-discounted products.

- **Discount Impact Analysis**:
  The project investigates how discounts affect sales volume, revenue, and stock levels. It also examines customer behavior regarding discounted items and the overall profitability of discount strategies.

## Results

- Recommendations on the data collection process were formulated.
- It was found that high discounts do not imply high revenue.
- Recommendations were formulated on optimizing discount strategies to balance sales growth and profitability.

## Tools & Technologies

- Python (Pandas, NumPy) for data manipulation and analysis
- Jupyter Notebook for an integrated code and report environment
- Matplotlib and Seaborn for data visualization

## Repository Contents

- `WBS_🦈_Eniac_Discount_Project.ipynb`: Jupyter notebook containing all code, analysis, and narrative report.
- `Eniac_Data/`: Folder containing all CSV data files used in the project.
- `Eniac Discount Analysis.pdf`: A detailed PDF report summarizing the findings (optional).

## How to Run

1. Clone the repository.
2. Ensure all CSV files are in the `Eniac_Data` directory.
3. Open the Jupyter notebook `WBS_🦈_Eniac_Discount_Project.ipynb`.
4. Run the cells sequentially to reproduce the analysis and visualizations.


