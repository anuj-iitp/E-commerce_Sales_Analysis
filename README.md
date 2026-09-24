# E-commerce Sales Analysis

An exploratory data analysis (EDA) of 5,000 e-commerce orders, done in a Jupyter Notebook with Python.

## Dataset

`ecommerce_sales_analytics_5000.csv` contains 5,000 orders (one per row) and 12 columns:

`order_id`, `order_date`, `customer_id`, `product_category`, `region`, `quantity`, `unit_price`, `discount`, `payment_method`, `delivery_days`, `customer_rating`, `revenue`

Dataset link: https://www.kaggle.com/datasets/abbas829/ecommerce-sales-dataset

## Main Analysis Areas

- Data inspection and basic statistics
- Missing values and duplicates check
- Overall sales and revenue
- Sales by product category
- Sales by region
- Payment methods
- Discounts
- Delivery days and customer ratings
- Relationships between numeric variables (correlations)

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

## Project Files

| File | Description |
|---|---|
| `ecommerce_sales_analysis.ipynb` | Analysis notebook (code and charts) |
| `ecommerce_sales_analytics_5000.csv` | Dataset |
| `requirements.txt` | Required Python libraries |
| `Project_Report.docx` | Project Report |

## Setup and Run

1. Install Python 3.9 or newer.
2. Put all project files in the same folder (the notebook reads the CSV from its own folder).
3. Install the libraries and Jupyter:

   ```bash
   pip install -r requirements.txt
   pip install notebook
   ```

4. Open the notebook:

   ```bash
   jupyter notebook ecommerce_sales_analysis.ipynb
   ```

5. Run all cells from top to bottom (**Run > Run All Cells**).

## Summary

This project analyzes e-commerce order data to see how revenue and order value vary by product category, region and payment method, how discounts relate to order value and quantity, and whether delivery time and customer ratings are related. It ends with a set of calculated results and correlations for the report.
