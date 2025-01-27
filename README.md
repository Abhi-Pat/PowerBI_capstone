# Power BI Project: Sales and Transaction Data Analysis for Consumer Electronics Company

## Overview

This repository contains a Power BI project designed for a **Consumer Electronics Company** that analyzed sales and transaction data from **2018 to 2022**. The company operates across **21 product categories** and has over **80+ sales employees**. The objective of this project is to deliver actionable insights on sales performance, employee performance, product trends, and profitability. The analysis provides data-driven insights to help make business decisions based on historical performance and forecast trends.

The key deliverables include interactive Power BI reports and dashboards, including essential business metrics, detailed analysis of sales, employee performance, and profitability, and user-friendly features for reporting and sharing.

## Business Requirements

The company outlined several key requirements for the analysis and reporting, which are detailed below:

### **1. Key Metrics for Business Overview:**
- **Total Income per Year**: Sum of the revenue generated each year from 2018 to 2022.
- **Total Number of Customers per Year**: Count of distinct customers each year.
- **Company Metrics**:
    - **Total Number of Employees**: Total count of sales employees.
    - **Total Number of Countries Served**: Count of countries the company operates in.
    - **Total Number of Products Offered**: Count of distinct products sold by the company.
    - **Total Number of Product Categories Offered**: Count of unique product categories the company deals with.

### **2. Top and Bottom Product and Employee Analysis:**
- **Top and Bottom Five Products** (by revenue): Identify the highest and lowest performing products in terms of sales.
- **Top and Bottom Five Product Categories**: Identify the highest and lowest performing product categories.
- **Top and Bottom Five Employees** (by revenue or quantity sold): Analyze employee performance based on total sales and/or quantity sold.
- **Top and Bottom Five Profitable States**: Analyze sales and profitability across different states, highlighting the top and bottom-performing states.

### **3. Employee Performance Metrics:**
- **Performance by Quantity Sold**: Analyze employee performance based on the number of units sold per year and quarter.
- **Performance by Profit After Discount**: Measure employee performance based on the profit they generate after discounts are applied, both annually and quarterly.

### **4. Quarterly Revenue Comparison:**
- **Revenue by Quarter**: Compare the generated revenue for each quarter across all four years (2018-2022) to identify if certain quarters generate higher sales than others.

### **5. Crucial Products for Revenue:**
- **Identifying Crucial Products**: Highlight which product names contribute significantly to the total revenue across all years.

### **6. Data Summary and Reporting:**
- **Summary of Data**: Provide an overall summary of the key metrics and findings.
- **Interactive Report with AI-driven Q&A**: Enable users to ask questions and receive AI-generated answers based on the data through Power BI’s Q&A feature.
  
### **7. Shareability and Mobile Access:**
- **Shareable Report**: Design reports that can be shared internally with employees and externally with stakeholders.
- **Mobile-Friendly Version**: Ensure the report is optimized for mobile devices so users can access the data on-the-go.
  
### **8. Printable Report:**
- **PDF Export**: Enable reports to be easily exported to PDF format for print distribution to selected users.

---

## Data Structure and Sources

The dataset used for analysis includes the following tables and columns:

- **Sales Data**: Transaction-level data, including product name, product category, quantity sold, revenue, and sale date.
- **Employee Data**: Employee information, including employee ID, name, region, and sales performance metrics.
- **Product Data**: Product-level data, including product name, category, cost, price, and other related attributes.
- **Customer Data**: Information about customers, including customer ID, location (state/country), and number of purchases.
- **Geographic Data**: Location-based data for regional (state/country) analysis, including sales and profitability per state.

These datasets were cleaned and transformed using **Power Query** and loaded into Power BI for analysis.

---

## Power BI Model Structure

### **Data Transformation and Cleaning:**
- Used **Power Query** to clean and transform the data:
    - Removed duplicates.
    - Fixed mismatched data types.
    - Imputed or excluded missing data.
    - Created calculated columns for important metrics such as profit margin and sales growth.
  
### **Relationships:**
- **Sales** table is connected to the **Employee** and **Product** tables via the respective IDs (Employee ID, Product ID).
- **Product** is linked to **Product Category** for category-level analysis.
- **Date** table is linked to the sales transactions to enable time-based filtering.

### **Measures and Calculations:**
- **Total Sales**: SUM of sales revenue.
- **Profit**: Sales Revenue - Cost.
- **Profit Margin**: (Profit / Sales Revenue) * 100.
- **Employee Ranking**: Ranking employees based on total sales or profit generated.
- **Quarterly Revenue Comparison**: A line chart to compare sales per quarter across years.
- **Year-over-Year Growth**: Comparison of sales revenue year-over-year.
  
---

## Key Visuals and Reports

### 1. **Executive Overview Dashboard:**
   - **Total Sales (Annual and Quarterly)**: Display total sales per year and compare quarterly performance over multiple years.
   - **Total Income per Year**: A simple line graph showing income by year.
   - **Top 5 Products/Bottom 5 Products**: A bar chart to show top and bottom products by revenue.
   - **Top 5 Categories/Bottom 5 Categories**: Visualizing the performance of product categories.
   - **Sales by Region/State**: A map or bar chart showing sales and profitability across various states.

### 2. **Employee Performance Dashboard:**
   - **Employee Ranking (by sales or quantity sold)**: A leaderboard to rank employees based on performance.
   - **Employee Performance per Quarter**: Bar charts showing performance by employee for each quarter.
   - **Profit After Discount by Employee**: Analysis of profit margins after discount for employees.

### 3. **Revenue and Trends Dashboard:**
   - **Revenue Comparison per Quarter**: Compare revenue per quarter across the years.
   - **Crucial Products for Revenue**: Identify products that are contributing most to revenue.
   - **Year-over-Year Revenue Growth**: Line chart or bar chart for year-over-year revenue growth.

### 4. **Product Insights Dashboard:**
   - **Top 5 Products**: Visual representation of the top-performing products.
   - **Bottom 5 Products**: Highlight the least performing products.
   - **Profitability of Products**: A table or bar chart comparing products by profitability.

### 5. **Interactive Q&A Feature:**
   - **Power BI Q&A**: Utilize the Q&A feature to allow users to type natural language questions and receive AI-generated answers based on the dataset.

---

## How to Use the Power BI Report

1. **Clone or Download** the repository to access the Power BI files.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Refresh the dataset to ensure the latest data is loaded.
4. Explore the **interactive dashboards** by using slicers and filters for different time periods, product categories, and employees.
5. Use the **Q&A feature** to type questions and receive instant data insights.
6. Share the report with team members or stakeholders by publishing to **Power BI Service**.
7. Export the report to **PDF** for easy printing or sharing offline.
8. Access the **mobile-optimized version** for on-the-go viewing.

---

## Shareability and Distribution

The Power BI report is designed to be:
- **Shareable** via Power BI Service, where internal staff and external stakeholders can view it.
- **Mobile-Friendly**, ensuring stakeholders can access the report from any device.
- Easily **exportable to PDF**, making it suitable for print distribution.

---

## Future Enhancements

- **Real-Time Data Integration**: Integrate real-time sales data for up-to-date reporting.
- **Advanced Predictive Analytics**: Incorporate machine learning models to predict future sales trends and product demand.
- **Customer Insights**: Add more customer demographics to understand purchasing patterns and behavior.
  
---

Feel free to fork or clone this repository and adapt the reports for your own business needs. Contributions, suggestions, and improvements are welcome!

