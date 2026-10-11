# BlinkIT Grocery Sales & Outlet Performance Analytics

## 📌 Project Overview

This project focuses on analyzing BlinkIT grocery sales and outlet performance using Microsoft Excel and Power BI. The objective is to understand sales patterns across different outlet formats, locations, and product categories, while exploring the relationship between shelf visibility, item ratings, and outlet age.

The analysis aims to help the merchandising team make informed decisions about product assortment, outlet performance, and future expansion.

## 🎯 Business Problem Statement

The VP of Merchandising needs a clear understanding of which products, categories, and outlet formats drive sales. Without a consolidated view of sales performance, shelf visibility, item ratings, and outlet age, assortment planning and outlet expansion decisions may rely on assumptions rather than data.

This project uses data cleaning, exploratory analysis, and interactive visualizations to investigate these business challenges.

## ❓ Business Questions

The project addresses the following questions:

1. **Outlet Performance:** Which outlet formats and locations drive the most sales?
2. **Product Category Performance:** Which item categories are over-performing or under-performing relative to shelf visibility?
3. **Ratings and Sales:** Do item ratings predict sales, or is there a relationship between ratings and sales?
4. **Outlet Age and Performance:** How does outlet age affect sales performance?

## 📊 Dataset Description

The project uses the BlinkIT grocery sales dataset provided with the case study.

- **Total Records:** 8,523 rows
- **Total Columns:** 12
- **Number of Outlets:** 10
- **Unique Items:** 1,559
- **Product Categories:** 16

The dataset contains information about:

- Item identifiers and product categories
- Item fat content and item weight
- Item visibility
- Outlet identifiers and establishment year
- Outlet location, size, and type
- Sales and item ratings

## 🛠️ Tools & Technologies

- **Microsoft Excel:** Data cleaning, data preparation, exploratory data analysis (EDA), and charts.
- **Microsoft Power BI:** Data visualization, sales performance analysis, and interactive dashboard development.

## 🔄 Project Workflow

### 1. Data Cleaning and Preparation — Excel

- Inspected the dataset for missing values and data quality issues.
- Standardized inconsistent labels in the Item Fat Content column.
- Handled missing Item Weight values using available item-level values and category medians.
- Treated zero values in Item Visibility as potential missing or invalid observations.
- Calculated outlet age using a defined reference year.
- Preserved the item-outlet level of the dataset during data preparation.

### 2. Exploratory Data Analysis (EDA) — Excel

Explored sales performance across outlet formats, outlet sizes, location tiers, and product categories.

The analysis also considered shelf visibility, item ratings, and outlet age to identify patterns relevant to the business questions.

### 3. Dashboard Development — Power BI

Developed a Power BI report to visualize grocery sales and outlet performance.

The dashboard supports analysis of:

- Overall sales performance
- Sales by outlet type
- Sales by outlet location
- Product category performance
- Item visibility in relation to sales
- Outlet age in relation to sales
- Item rating distribution

### 4. Business Insights

The analysis is designed to help the merchandising team understand sales patterns, evaluate product and outlet performance, and identify areas that may require further investigation.

Specific findings and recommendations should be based on the results shown in the Excel analysis and Power BI report.

## 💡 Key Insights

The project investigates four key areas:

- **Outlet Performance:** Comparing sales across outlet formats and locations.
- **Product Category Performance:** Examining category sales alongside item visibility.
- **Ratings and Sales:** Exploring whether item ratings are associated with sales performance.
- **Outlet Age:** Investigating how outlet age relates to sales.

Actual findings will be documented based on the completed analysis and dashboard results.

## 📁 Project Files

| File Name | Description |
|---|---|
| `BlinkIT_report.pbix` | Power BI report for grocery sales and outlet performance analysis. |
| `BlinkIT_cleaned.xlsx` | Cleaned Excel dataset used for analysis. |
| `BlinkIT_Grocery_Case_Study.pdf` | Case study brief describing the business background, data quality issues, and analytical requirements. |
| `BlinkitQuestions.txt` | Text file containing the business questions for the project. |

## 📈 Business Value

This project demonstrates how retail sales data can be organized and analyzed to support business decision-making.

The analysis can help stakeholders:

- Compare sales performance across outlet formats and locations.
- Evaluate product category performance and shelf visibility.
- Investigate the relationship between item ratings and sales.
- Understand sales patterns across outlets of different ages.
- Make more informed product assortment and outlet expansion decisions.

## 📝 Conclusion

The BlinkIT Grocery Sales & Outlet Performance Analytics project demonstrates a practical approach to retail data analytics using Excel and Power BI. By combining data preparation, exploratory analysis, and interactive visualizations, the project aims to turn raw grocery sales data into meaningful business insights.

---

**Project Type:** Data Analytics | Retail Analytics | Business Intelligence

**Tools:** Microsoft Excel | Microsoft Power BI
