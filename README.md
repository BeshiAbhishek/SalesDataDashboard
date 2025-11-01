# 🧾 Sales Data Dashboard (Excel Project)

## 📘 Project Overview

This project showcases an interactive Excel Dashboard built from the Superstore dataset.
The goal is to analyze and visualize key sales insights — including total sales, profits, trends, and customer performance — through dynamic pivot tables and slicer-driven dashboards.

It demonstrates:

Data cleaning & preprocessing

Pivot table-based analysis

Interactive dashboards for business insights

Professional data structuring for reproducibility

## ⚙️ Data Cleaning Process

Performed in Superstore_Cleaned.xlsx

Converted Order Date & Ship Date to uniform dd-mm-yyyy format

Added new derived columns:

Days-to-Ship → Ship Date - Order Date

Profit Margin → Profit / Sales

Sales Category → Categorized into Low, Medium, High

Applied Data Validation lists for consistent entry (Ship Mode, Segment, Region, Category, Sub-Category)

## 📊 Analysis Performed

Pivot table analyses were created in the Analysis Workbook to summarize sales and profit insights:

| # | Analysis Type             | Rows          | Columns          | Values        |
| - | ------------------------- | ------------- | ---------------- | ------------- |
| 1 | Total Sales per Category  | Category      | Segment          | Sum of Sales  |
| 2 | Sum of Profit by Region   | Region        | Category         | Sum of Profit |
| 3 | Monthly Sales Trend       | Category      | Years → Quarters | Sum of Sales  |
| 4 | Top 10 Customers by Sales | Customer Name | —                | Sum of Sales  |

## 📈 Dashboard Highlights

Built in the Dashboard Workbook, featuring multiple interactive visuals and slicers.
| Dashboard                 | Visualization          | Slicers Used                       |
| ------------------------- | ---------------------- | ---------------------------------- |
| Total Sales per Category  | Clustered Column Chart | Region, Segment, Year              |
| Sum of Profit by Region   | Bar Chart              | Region, Segment, Year              |
| Monthly Sales Trend       | Line Chart             | Region, Segment, Year              |
| Top 10 Customers by Sales | Bar Chart              | Region, Segment, Year              |
| All Dashboards            | Combined View          | All three slicers applied globally |

## 📋 Lookup Lists

A separate LookupLists Workbook ensures clean and standardized entries for data validation.
Contains lists for:

Ship Mode

Segment

Region

Category

Sub-Category

## 📖 Data Dictionary

Documented all fields, their descriptions, datatypes, lookups, and example values.
Helps in better understanding of dataset and ensuring consistent data handling across sheets.

## 💡 Key Learnings

Gained hands-on experience with Excel data cleaning, validation, and analysis

Designed an interactive dashboard with slicers & pivot charts

Structured project workflow suitable for version control (GitHub)

Improved understanding of data visualization & storytelling in Excel

## 🚀 Next Steps

Automate report generation using Python or Power BI

Integrate new KPIs (e.g., sales forecast, profit by product category)

Add trend comparison with previous years

## 🧠 Tools & Skills Used

Microsoft Excel

Data Cleaning & Validation

Pivot Tables & Charts

Dashboard Design

Git & GitHub for version control

Data Analysis & Visualization Concepts

## 👨‍💻 Author
Name: Beshi Abhishek              
Email: beshiabhishek@gmail.com
Mobile: +91 7981031423
LinkedIn: www.linkedin.com/in/abhishekbeshi
"Data has stories — you just need the right lens to see them."

