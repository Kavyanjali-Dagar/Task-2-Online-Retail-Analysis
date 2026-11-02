# Task 2 - Online Retail Data Analysis

## Project Overview

This project was completed as part of **Task 2: Hands-On Data Lab Implementation**. The project demonstrates practical data analysis using Python and Jupyter Notebook.

The **UCI Online Retail dataset** was used to analyze retail transactions, product performance, revenue, country-wise sales, and monthly revenue trends.

## Objectives

- Set up a Python and Jupyter Notebook data analysis environment.
- Load and explore a real-world dataset.
- Clean and preprocess transactional data.
- Perform data manipulation and statistical analysis.
- Calculate transaction-level revenue.
- Analyze products, countries, and monthly sales.
- Create meaningful data visualizations.
- Identify useful business insights from the data.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Excel dataset

## Dataset

The dataset used in this project is the **Online Retail dataset** from the UCI Machine Learning Repository.

Dataset source: https://archive.ics.uci.edu/dataset/352/online%2Bretail

The original dataset contains 541,909 records and 8 variables.

## Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records.
- Removed cancelled transactions.
- Removed transactions with invalid quantities.
- Removed transactions with invalid unit prices.
- Created a Revenue column using Quantity × UnitPrice.
- Converted InvoiceDate into a proper date format for monthly analysis.

After cleaning, the dataset contained **524,878 valid records**.

## Analysis Performed

The project includes:

- Revenue analysis
- Quantity analysis
- Country-wise transaction analysis
- Country-wise revenue analysis
- Product-wise revenue analysis
- Monthly revenue analysis
- Correlation analysis

## Visualizations

The following visualizations were created:

- Top 10 Products by Revenue
- Monthly Revenue Trend
- Distribution of Transaction Revenue
- Quantity and Unit Price analysis
- Correlation Heatmap

## Key Findings

- Total revenue was approximately **10.64 million**.
- Total quantity sold was **5,572,420 units**.
- The United Kingdom had the highest number of transactions and revenue.
- November 2011 recorded the highest monthly revenue.
- Quantity and Revenue had a strong positive correlation of approximately **0.91**.
- Revenue was highly right-skewed, with most transactions having relatively low revenue and a small number having very high revenue.

## Project Files

- `Task_2_Online_Retail_Analysis.ipynb` — Complete Jupyter Notebook containing the analysis and visualizations.
- `README.md` — Project documentation.

## Conclusion

This project provided practical experience in data loading, data cleaning, data manipulation, statistical analysis, visualization, and interpretation using Python. It demonstrates how raw retail transaction data can be transformed into meaningful insights through a structured data analysis process.
