# Sales Data Analysis Project

## Project Overview

This analysis was conducted to understand sales performance based on products, cities, and daily trends using a fictional sales dataset.

## Dataset

* File Name: `sales_data.csv`
* Columns:

  * Order Date
  * City
  * Product
  * Quantity
  * Unit Price
  * Total Sales

## Tools & Libraries

* Python 3
* Pandas
* Matplotlib
* Seaborn

## Analysis Performed

1. **Data Cleaning**:

   * Created a new column `Total Sales` from `Quantity * Unit Price`.
2. **Product Analysis**:

   * Identified the product with the highest total sales.
3. **City Analysis**:

   * Identified the city with the highest total sales.
4. **Sales Trend**:

   * Created a daily sales trend graph.

## Key Findings

* **Top-selling product**: Laptop
* **City with the highest sales**: Jakarta
* **Additional insight**: A significant spike in sales occurred on January 10, 2024.

## How to Run This Project

1. Ensure Python 3 is installed.
2. Install the required libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the `analysis.ipynb` notebook using Jupyter Notebook.

## Author

Muhammad Syarip Qorni
[GitHub Profile](https://github.com/nambi02)