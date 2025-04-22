#  Global Superstore Data Visualization Project

##  Dataset Overview

File Name: `global_superstore_2016.xlsx`  
Description:  
This dataset contains sales, customer, order, shipping, and regional information for a global retail store. It includes detailed data points across product categories, sales regions, delivery timelines, and customer transactions.

##  Project Objectives

The purpose of this project is to visualize and gain insights from the sales data by focusing on the following metrics:

1. Sales by Segment
2. Sales by Region
3. Top 10 Customers by Sales
4. Loss by Product Name (negative profit)
5. Profit by Product Name
6. Total Sales
7. Quantity Sold
8. Average Delivery Days
9. Returned Orders

##  Tools Used

- Power BI

## Visualizations and Analysis

### 1. Sales by Segment
- Group by `Segment` and sum the `Sales`.
- Visual: Pie chart.

### 2. Sales by Region
- Group by `Region` and sum the `Sales`.
- Visual: Donut chart

### 3. Top 10 Customers by Sales
- Group by `Customer Name` and sum the `Sales`.
- Sort and select top 10.
- Visual:  bar chart.

### 4. Loss by Product Name
- Filter rows where `Profit < 0`, group by `Product Name`, sum `Profit`.
- Sort in ascending order to show maximum losses.
- Visual: Bar chart.

### 5. Profit by Product Name
- Group by `Product Name`, sum `Profit`, sort descending.
- Visual: Bar chart.

### 6. Total Sales
- Sum of `Sales` column.
- Display as a card.

### 7. Quantity Sold
- Sum of `Quantity` column.
- Display as a card.

### 8. Average Delivery Days
- Calculate difference between `Ship Date` and `Order Date` per row.
- Compute average across all orders.
- Display as a card.

### 9. Returned Orders
- Identify from `Returned` column (if present), or use `Status = Returned` if applicable.
- Count and visualize the frequency.
- Display as a card.
