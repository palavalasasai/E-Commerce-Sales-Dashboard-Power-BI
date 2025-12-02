📊 E-Commerce Sales Dashboard – End-to-End Power BI Project

This project focuses on building a fully interactive E-Commerce Sales Dashboard using Power BI to analyze sales performance, customer behavior, product trends, and regional insights. It helps businesses track KPIs, identify high-value customers, optimize operations, and make data-driven decisions with a clean, modern UI.

📌 Project Overview

The dashboard provides a 360° analytical view of:

💰 Total Revenue (Amount)

📦 Total Quantity Sold

📈 Total Profit

🛒 Category & Sub-Category performance

🌍 State & City level sales

👥 Top Customers

💳 Payment mode insights

📆 Monthly Profit Trends

An elegant Dark Green + Gold theme is applied for premium, business-grade storytelling.

🎯 Objectives

Track sales, profit, and order demand across key business metrics

Understand buyer preferences based on location, payment mode, and product category

Identify best-performing states, cities, products, and customers

Visualize trends in monthly performance and profit contributions

Provide interactive insights through slicers and dynamic charts

🧩 Dataset Description

File: Ecommerce_Sales_5000_Rows.csv
Rows: 5,000
Columns: 10+

Column	Description	Type
OrderID	Unique order identifier	Categorical
OrderDate	Date of purchase	Date
CustomerName	Customer name	Categorical
City	Customer city	Categorical
State	Customer state	Categorical
Category	Product category	Categorical
Sub-Category	Product sub-category	Categorical
PaymentMode	UPI, Credit Card, COD, etc.	Categorical
Quantity	Units ordered	Numeric
Amount	Sales amount	Numeric
Profit	Profit earned	Numeric
🔧 Feature Engineering (DAX)
Month Name
MonthName = FORMAT([OrderDate], "MMMM")

Month Number
MonthNumber = FORMAT([OrderDate], "MM")

Year
Year = YEAR([OrderDate])

Total Amount
Total Amount = SUM(Ecommerce_Sales[Amount])

Total Profit
Total Profit = SUM(Ecommerce_Sales[Profit])

📈 Dashboard Visuals
🟩 KPI Cards

Total Amount

Total Quantity

Total Profit

🥧 Donut Charts

Quantity by Category

Quantity by Payment Mode

📊 Bar Charts

Sales by Customer

Sales by State

Profit by Sub-Category

Monthly Profit Trend

🌍 Map Visualization

State-level Sales Distribution

Location-based insights

🎛 Filters (Slicers)

State

City

🛠 Tools & Technologies Used
Power BI

Power Query (Data cleaning + Preparation)

DAX (Feature creation)

Interactive Visualizations

Custom JSON Theme

KPI Cards, Donut Charts, Bar Charts, Maps

Supporting Tools

Excel / CSV for raw data

Figma (optional for UI planning)

📂 Repository Structure
ecommerce-powerbi-dashboard/
│
├── data/
│   └── Ecommerce_Sales_5000_Rows.csv
│
├── powerbi/
│   └── Ecommerce_Dashboard.pbix
│
├── theme/
│   └── Ecommerce_DarkGold_Theme.json
│
├── visuals/
│   └── dashboard_preview.png
│
├── README.md
└── LICENSE

💡 Insights Summary

Clothing, Electronics, and Furniture generate the highest demand

UPI and Credit Card dominate payment preferences

Maharashtra & Madhya Pradesh drive major revenue

January, March, and June show higher profit contribution

Top customers significantly impact total revenue

Sub-categories like Sarees, Accessories, and Mobiles show strong profitability

🚀 Future Enhancements

Add forecasting using Power BI’s analytics pane

Add RFM customer segmentation

Connect to a real-time SQL database

Build an automated refresh pipeline

Deploy dashboard to Power BI Service

👨‍💻 Author

Palavalasa Sai
📧 palavalasasai42@gmail.com

💼 Data Analytics Enthusiast | Python | SQL | Power BI | Visualization

📜 License

This project is open-source and available under the MIT License.
