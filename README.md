# 🌍 Global Multi-Region Sales & Revenue Analytics Platform

An interactive Excel dashboard that analyzes sales, revenue and profitability across
6 countries, 53 states and 3 product categories, built on 113,000+ transaction records
(Jan 2011 – Jul 2016).

## 📌 Project Overview
This project turns raw transactional sales data into a decision-ready dashboard.
It answers key business questions: Which regions drive revenue? Which products are most
profitable? Which customer segments buy the most? How have sales trended over time?

## 📊 Key Metrics
| Metric | Value |
|---|---|
| Total Orders (Quantity) | 1,345,316 |
| Total Revenue | 95.18M |
| Total Production Cost | 53.05M |
| Total Profit | 42.13M |
| Overall Profit Margin | ~44% |

## 🔍 Key Insights
- **Bikes dominate**: ~73% of total revenue (69.2M), with Road Bikes and Mountain Bikes the top profit drivers.
- **Accessories** have the highest margin (~63%) and the highest order volume (70K+ transactions).
- **United States** is the largest market (30.8M revenue), followed by Australia (25.4M) and the UK (11.1M).
- **Adults (35–64)** contribute the most revenue (~50%), followed by Young Adults (25–34).
- Revenue grew strongly from 2011–12 (~10M/yr) to 2015 (22.4M), the peak year.
- Revenue is split almost evenly between male and female customers.

## 🛠️ Features
- **Interactive dashboard** with slicers (Country, Product Category, Product, Age Group, Gender) and a Timeline filter on Date
- **9 charts**: month/year-wise orders, revenue and profit trends; country-wise revenue and profit; age-group analysis; product-wise orders
- **KPI cards** for total orders, cost, revenue and profit
- **Pivot-table analysis sheet** for state-wise profit, country-wise revenue and age-group breakdowns
- **Formula-driven data model**: Total Cost, Revenue and Profit are calculated from quantity, unit cost and unit price; date fields (Day, Month, Year) are derived from the order date

## 🧰 Tools & Techniques
Microsoft Excel · Pivot Tables · Pivot Charts · Slicers & Timelines · Excel Formulas (TEXT, DAY, YEAR) · Data Modeling · Dashboard Design

## 📂 Dataset
| Field | Description |
|---|---|
| Date, Day, Month, Year | Order date and derived date fields |
| Customer_Age, Age_Group, Gender | Customer demographics |
| Country, State | Sales geography |
| Product_Category, Sub_Category, Product | Product hierarchy (3 categories, 17 sub-categories, 130 products) |
| Order_Quantity, Unit_Cost, Unit_Price | Transaction inputs |
| Total Cost, Revenue, Profit | Calculated measures |

## 📁 Repository Structure
- `Global_Multi-Region_Sales_&_Revenue_Analytics_Platform.xlsx` – dataset, pivot analysis and dashboard
- `README.md` – project documentation

## 🚀 How to Use
1. Download the `.xlsx` file and open it in Microsoft Excel (2016 or later recommended for slicers/timelines).
2. Go to the **Dashboard** sheet.
3. Use the slicers and the timeline to filter by country, product, age group, gender or date range.

## 👤 Author
**Chandrakant Ghugul** – Data Analyst
