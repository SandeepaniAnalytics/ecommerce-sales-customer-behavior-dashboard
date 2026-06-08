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


![Dashboard Overview](https://github.com/SandeepaniAnalytics/ecommerce-sales-customer-behavior-dashboard/blob/main/screenshots/page1_sales_overview.png)

![Dashboard Overview](https://github.com/SandeepaniAnalytics/ecommerce-sales-customer-behavior-dashboard/blob/main/screenshots/page2_customer_behavior.png)

![Dashboard Overview](https://github.com/SandeepaniAnalytics/ecommerce-sales-customer-behavior-dashboard/blob/main/screenshots/page3_delivery_operations.png)



---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development and visualization |
| **DAX** | Measures, KPI calculations and calculated columns |
| **Power Query** | Data transformation and cleaning |
| **Data Modeling** | Date table relationship and schema design |
| **CSV** | Source data format |

---

## 📁 Repository Structure

```
📦 ecommerce-sales-customer-behavior-dashboard
 ┣ 📂 data
 ┃ ┗ 📄 ecommerce_customer_behavior_dataset.csv
 ┣ 📂 screenshots
 ┃ ┗ 🖼️ page1_sales_overview.png
 ┃ ┗ 🖼️ page2_customer_behavior.png
 ┃ ┗ 🖼️ page3_delivery_operations.png
 ┣ 📄 ECommerce_Dashboard.pbix
 ┗ 📄 README.md
```

---

## 🏅 Skills Demonstrated

| Skill | Description |
|---|---|
| **Business Intelligence** | Translating raw transaction data into actionable business insights |
| **Dashboard Design** | 3-pages structured layout with consistent theme |
| **DAX Calculations** | 20+ custom measures for KPIs, MoM growth, and customer segmentation |
| **Time Intelligence** | MoM growth indicators for sales, orders, and units sold |
| **Field Parameters** | Single toggle dynamically controlling 3 linked visuals simultaneously |
| **Power Query** | Data type fixing, column renaming, and transformation |
| **Scatter Plot Analysis** | Delivery time vs customer rating correlation with trend line |
| **Conditional Formatting** | Color-coded MoM indicators and delivery zone colors |

---

## 👤 Author

**Sandeepani Rathnayake** <br>
*Power BI & Data Analytics Enthusiast*

