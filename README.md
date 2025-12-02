# E-Commerce-Sales-Dashboard-Power-BI
This project showcases a fully interactive E-Commerce Sales Dashboard built using Power BI, designed to analyze sales, profit, and customer behavior across multiple dimensions.
🚀 Project Overview

The goal was to create a visually appealing and insight-driven dashboard to help businesses track:

Total Sales (Amount)

Total Quantity Sold

Total Profit

Top-Performing Categories & Sub-Categories

State-wise & City-wise Sales

Customer Contribution

Profit Trends (Monthly / Quarterly)

Payment Mode Performance

A modern Dark-Teal + Gold UI theme was applied for a premium analytics experience.

🛠 Tools & Technologies Used
Tool / Tech	Purpose
Power BI Desktop	Dashboard creation & DAX modeling
Power Query	Data transformation & cleaning
DAX	Calculated columns & measures
Custom JSON Theme	Dark-Gold UI styling
CSV Dataset	5,000-row synthetic e-commerce dataset
📈 Key Features
✅ 1. KPI Summary Cards

Total Amount: 51M

Total Quantity: 15K

Total Profit: 10M

✅ 2. Donut Charts

Quantity by Category

Quantity by Payment Mode

✅ 3. Bar Charts

Amount by Customer Name

Amount by State

Profit by Sub-Category

Profit by Month

✅ 4. Interactive Filters

State

City

✅ 5. Map Visualization

Bubble map for sales distribution by location

📂 Project Files
File	Description
Ecommerce_Sales_5000_Rows.csv	Dataset used in the dashboard
Ecommerce_DarkGold_Theme.json	Custom theme file
Ecommerce_Sales_Dashboard.pbix	Power BI dashboard file
README.md	Project documentation
🧠 DAX Calculations Used
Month Name
MonthName = FORMAT([OrderDate], "MMMM")

Month Number
MonthNumber = FORMAT([OrderDate], "MM")

Year
Year = YEAR([OrderDate])

Total Profit
Total Profit = SUM(Ecommerce_Sales[Profit])

Total Amount
Total Amount = SUM(Ecommerce_Sales[Amount])

📊 Dashboard Preview (AI Mockup)

⭐ Learning Outcomes

Designing clean, business-focused dashboards

Applying custom Power BI themes

Creating KPIs & DAX measures

Data modeling best practices

Visual storytelling through analytics
