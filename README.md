# E-Commerce-Trend-Analysis-Dashboard-Power-BI-Project-
This repository contains my end-to-end Power BI project analyzing e-commerce performance for 2010–2011.  
🔧 Data Preparation

Cleaned raw Online Retail dataset in Power Query

Removed nulls, duplicates, invalid entries

Standardized data types (dates, numeric values)

Created calculated columns (TotalPrice, Month Initial, Month Number, Quarter)

Fixed inconsistencies in StockCode & Customer fields

📐 Data Modeling

Designed a star schema consisting of:

Fact_Orders

InvoiceNo, CustomerID, StockCode

Quantity, UnitPrice, TotalPrice

InvoiceDate

Customer_Dim

CustomerID, Country

Product_Dim

StockCode, Product

Date_Dim

Date, MonthInitial, MonthName

MonthNumber, Quarter

📊 Measures & DAX

Key measures created:

Total Sales

Total Orders

Total Quantity

Average Order Value

YoY Growth KPIs

Quarter Performance

Dynamic parameter for metric switching (Sales/Orders/Quantity).

📈 Dashboard Features

KPI Cards with YoY comparison

Month-wise trends

Product-wise & Customer-wise breakdown

Country-level sales map

Quarter performance donut chart

Fully interactive with slicers
