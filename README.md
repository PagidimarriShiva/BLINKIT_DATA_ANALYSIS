# Blinkit Sales Data Analysis
## Project Overview
This project analyzes Blinkit dataset to uncover insights into sales, items, outlets, and pricing trends. The analysis is done using Python (Pandas, NumPy, Matplotlib, Seaborn) in a Jupyter Notebook.
### The goal of this project is to:
Clean and preprocess raw data (handle null values, data types, and formatting).

Perform exploratory data analysis (EDA) to understand sales distribution and patterns.

Apply statistical and aggregation techniques to summarize data.

Visualize trends using Matplotlib and Seaborn for better business insights.
## Dataset

The dataset contains the following columns:

Item_Identifier – Unique ID for each item

Item_Weight – Weight of the item

Item_Fat_Content – Whether the item is low-fat, regular, etc.

Item_Visibility – Visibility of the item in the store

Item_Type – Category of the item

Item_MRP – Maximum retail price of the item

Outlet_Identifier – Unique store ID

Outlet_Establishment_Year – Year when the outlet was established

Outlet_Size – Size of the outlet (small/medium/large)

Outlet_Location_Type – Tier of the city where the outlet is located

Outlet_Type – Type of outlet (grocery store, supermarket, etc.)

Item_Outlet_Sales – Total sales for the item in that store

## Technologies Used

Python

Pandas – Data manipulation & cleaning

NumPy – Numerical computations

Matplotlib – Data visualization

Seaborn – Statistical plots

Jupyter Notebook

## Steps Performed
### Data Cleaning & Preprocessing

Removed or imputed null values (using mean/median).

Standardized inconsistent values (e.g., "LF", "low fat" → "Low Fat").

Converted Outlet Establishment Year into date format.

Checked dataset properties: .info(), .describe(), .shape, .size.

## Exploratory Data Analysis (EDA)

Top 5 & Bottom 5 rows for quick look at dataset.

Summary statistics (mean, median, mode, aggregations).

Distribution of item sales across outlets.

Item sales vs. MRP analysis.

Outlet size & location impact on sales.

## Data Visualization

Histograms and bar plots for item sales.

Boxplots to detect outliers.

Correlation heatmap using Seaborn.

Trend analysis with line plots.

## Key Insights

Outlet Size & Location strongly impact total sales.

Items with higher visibility & MRP tend to sell more.

Standardizing categorical values improved data consistency.

Sales trend varies across Supermarket vs. Grocery Store.

# ✨ Author

👤 shiva pagidimarri

📧 Email: ppagidimarrishiva@gmail.com

💼 LinkedIn:www.linkedin.com/in/pagidimarri-shiva-55b076355
