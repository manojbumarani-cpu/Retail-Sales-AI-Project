# AI-Powered Retail Sales Analytics and Demand Forecasting

## Project Overview

This project analyzes retail sales data and uses machine learning to forecast future monthly sales.

The project uses the Sample Superstore dataset to identify sales and profit patterns across categories, regions, and products.

## Objectives

- Analyze historical retail sales data
- Identify high-performing categories and regions
- Analyze product-level sales performance
- Visualize monthly sales trends
- Create features for demand forecasting
- Develop a machine learning forecasting model
- Evaluate forecasting performance

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning

Linear Regression was used for monthly demand forecasting.

The model uses:

- Month
- Year
- Previous month's sales
- Sales from two months earlier
- Sales from three months earlier
- 3-month rolling average

## Key Results

- Total Sales: approximately 2.33 million
- Total Profit: approximately 0.29 million
- Highest Sales Category: Technology
- Highest Sales Region: West
- Most Profitable Category: Technology
- Model R²: 0.6574
- Model MAE: approximately 10,251.51

## How to Run

1. Install Python 3 or later.
2. Open the project in VS Code.
3. Install the required libraries:

```bash
pip install -r requirements.txt