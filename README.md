# 🛍️ E-Commerce Sales & Customer Behavior Dashboard
### Power BI Dashboard | E-Commerce Sales Analytics 

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![CSV](https://img.shields.io/badge/CSV-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

## 📋 Project Overview

An **interactive Power BI dashboard** built to analyze **17K+ transactions** from a online retail platform spanning **January 2023 to March 2024**. The dashboard provides end-to-end visibility into sales performance, customer behavior, delivery operations, and product category trends enabling data-driven decisions for marketing, operations, and management teams.

---

## 🎯 Purpose of the Dashboard

The purpose of this dashboard is to help business users and decision-makers:

- 💰 Monitor total sales, orders, and revenue trends over time
- 📦 Identify top-performing and underperforming product categories
- 🚚 Understand how delivery performance impacts customer satisfaction
- 📱 Analyse device and payment method behavior to optimize conversion
- 👥 Segment customers by age group to prioritize retention investment
- 🌍 Compare revenue performance across 10 cities
- 📈 Track MoM growth indicators across sales, orders, and units sold

---

## 🗃️ Dataset

| Detail | Value |
|---|---|
| **Source** | Kaggle |
| **Total Transactions** | 17K+ |
| **Unique Customers** | 5,000 |
| **Product Categories** | 8 |
| **Cities** | 10 cities |
| **Date Range** | January 2023 – March 2024 |
| **Source Format** | CSV |
| **Total Columns** | 18 |

### Key Dataset Columns

| Column | Description |
|---|---|
| `Order_ID` | Unique transaction identifier |
| `Customer_ID` | Unique customer identifier |
| `Date` | Transaction date (Jan 2023 – Mar 2024) |
| `Age` | Customer age in years (18–75) |
| `Gender` | Male / Female / Other |
| `City` | Customer city (10 major Turkish cities) |
| `Product_Category` | 8 product categories |
| `Unit_Price` | Price per unit |
| `Quantity` | Units purchased per transaction (1–5) |
| `Discount_Amount` | Discount applied to order |
| `Total_Amount` | Final amount paid after discount |
| `Payment_Method` | Credit Card, Debit Card, Digital Wallet, Bank Transfer, Cash on Delivery |
| `Device_Type` | Mobile, Desktop, Tablet |
| `Session_Duration_Minutes` | Time spent on website per session (1–120 min) |
| `Pages_Viewed` | Pages viewed per session (1–50) |
| `Is_Returning_Customer` | True / False |
| `Delivery_Time_Days` | Delivery duration in days (1–30) |
| `Customer_Rating` | Customer satisfaction rating (1–5 stars) |

---

## 📊 Dashboard
Single-page end-to-end snapshot covering sales performance, customer behavior, and delivery operations.

**KPI Cards**
- Total Sales
- Total Orders
- Units Sold
- Avg Order Value
- Returning Rate
- Average Rating

**Visuals**

| Visual | Type |
|---|---|
| Monthly Performance Trend | Line chart |
| Product Category Performance | Horizontal bar chart |
| City Performance Overview | Treemap |
| Delivery Days vs Customer Rating | Scatter plot |
| Orders by Device Type | Donut chart |
| Customer Engagement by Device | Clustered bar chart |
| Orders by Payment Method | Bar chart |
| Revenue by Age Group | Bar chart |

![Dashboard Overview](https://github.com/SandeepaniAnalytics/ecommerce-sales-customer-behavior-dashboard/blob/main/dashboard-preview.png)

---

## 💡 Key Business Insights

📉 **Revenue dropped 45% in April 2023** = from $2.8M to $1.5M - Q1 seasonality or campaign-driven; root cause requires investigation

⚡ **Electronics drives 48% of total revenue** - single category concentration is a major business risk if supply or pricing is disrupted

🚚 **Delivery beyond 15 days correlates with ratings below 3.5★** - logistics performance directly impacts customer satisfaction and retention

🏙️ **Istanbul accounts for 26% of all revenue** = geographic over-reliance; Bursa and Antalya show untapped growth potential

📱 **Mobile = 56% of orders but lower AOV than desktop** - mobile checkout experience is the largest single revenue uplift opportunity

👥 **26–35 and 36–45 age groups are the highest spending segments** = priority targets for loyalty and retention campaigns

📈 **December shows MoM recovery** - Q4 seasonal uplift; plan campaigns to accelerate this trend year-on-year

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development and visualization |
| **DAX** | Measures, KPI calculations and calculated columns |
| **Power Query** | Data transformation and cleaning |
| **Data Modeling** | Date table relationship and schema design |
| **CSV** | Source data format |
| **GitHub** | Version control and project sharing |

---

## 📁 Repository Structure

```
📦 ecommerce-sales-customer-behavior-dashboard
 ┣ 📂 data
 ┃ ┗ 📄 ecommerce_customer_behavior_dataset.csv
 ┣ 🖼️ dashboard_overview.png
 ┣ 📄 ECommerce_Dashboard.pbix
 ┗ 📄 README.md
```

---

## 🏅 Skills Demonstrated

| Skill | Description |
|---|---|
| **Business Intelligence** | Translating raw transaction data into actionable business insights |
| **Dashboard Design** | Single-page structured layout with consistent theme |
| **DAX Calculations** | 15+ custom measures for KPIs, MoM growth, and customer segmentation |
| **Time Intelligence** | MoM growth indicators for sales, orders, and units sold |
| **Calculated Columns** | Age group, delivery zone, discount flag, and session group classification |
| **Field Parameters** | Single toggle dynamically controlling 3 linked visuals simultaneously |
| **Power Query** | Data type fixing, column renaming, and transformation |
| **Scatter Plot Analysis** | Delivery time vs customer rating correlation with trend line |
| **Conditional Formatting** | Color-coded MoM indicators and delivery zone colors |

---

## 👤 Author

**Sandeepani Rathnayake** <br>
*Power BI & Data Analytics Enthusiast*

