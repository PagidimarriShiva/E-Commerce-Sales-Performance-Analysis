# 🛒 E-Commerce Sales Performance Analysis

> Transforming raw transactional data into actionable business insights using Python, SQL, and Power BI.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat&logoColor=black)

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Dataset Information](#-dataset-information)
- [Tools & Technologies](#️-tools--technologies)
- [Project Workflow](#-project-workflow)
- [Key Findings](#-key-findings)
- [Visualizations](#️-visualizations)
- [Folder Structure](#-folder-structure)
- [How to Run](#️-how-to-run)
- [Future Improvements](#-future-improvements)
- [Conclusion](#-conclusion)

---

## 📝 Project Overview

This project analyzes e-commerce transactional data to uncover **revenue trends**, **regional performance**, **product category insights**, and **customer purchasing behavior**. The goal was to transform raw sales data into actionable business insights using data cleaning, exploratory analysis, and interactive visualization.

The final output includes KPI analysis and an interactive **Power BI dashboard** to support data-driven decision-making.

---

## 🎯 Problem Statement

The business wanted answers to the following questions:

- Which **product categories** drive the most revenue?
- Which **regions** contribute the highest sales?
- How do **discounts** impact quantity sold?
- Which **payment methods** are most preferred?
- What insights can improve **revenue and customer satisfaction**?

---

## 📂 Dataset Information

The dataset contains transactional e-commerce records with the following fields:

| Field | Description |
|---|---|
| `order_id` | Unique order identifier |
| `order_date` | Date of transaction |
| `product_category` | Category of product sold |
| `price` | Original unit price |
| `discount_percentage` | Discount applied (%) |
| `discounted_price` | Price after discount |
| `quantity_sold` | Units sold per order |
| `customer_region` | Geographic region of customer |
| `payment_method` | Payment channel used |
| `rating` | Customer rating |
| `review_count` | Number of reviews |
| `total_revenue` | Final revenue per order |

**Dataset Summary:**

| Metric | Value |
|---|---|
| 💰 Total Revenue | ₹32,866,573.74 |
| 📦 Total Quantity Sold | 149,970 units |
| 🌍 Regions Covered | Multiple |
| 🗂️ Categories Analyzed | Multiple |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python (Pandas, Matplotlib) | Data cleaning & EDA |
| Power BI | Interactive dashboard & visualization |
| DAX | KPI measures and calculated metrics |
| Excel | Initial data validation |

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Checked for missing values and duplicates
- Validated `discounted_price` calculations against source fields
- Verified `total_revenue` formula consistency
- Standardized date formats across all records

### 2️⃣ Exploratory Data Analysis (EDA)
- Revenue by product category
- Revenue by region
- Revenue by payment method
- Monthly revenue trends
- Discount vs. quantity sold correlation

### 3️⃣ Business Analysis

Calculated core KPIs:

| KPI | Description |
|---|---|
| Total Revenue | Sum of all order revenue |
| Total Orders | Count of unique orders |
| Average Order Value (AOV) | Revenue ÷ Orders |
| Revenue Contribution % | Category / Region share |

- Identified top-performing regions and categories
- Analyzed impact of discount strategy on sales volume

### 4️⃣ Visualization
- Built interactive Power BI dashboard with KPI cards
- Created bar charts, line charts, and trend visuals
- Implemented slicers for region and category filtering

### 5️⃣ Insights Generation
- Translated analysis into business recommendations
- Highlighted revenue concentration risks
- Identified growth opportunities by segment

---

## 📈 Key Findings

| # | Finding |
|---|---|
| 🌍 | **Middle East** contributes ~25% of total revenue — top-performing region |
| 💄 | **Beauty** category leads with ~17% revenue contribution |
| 💳 | **Wallet payments** account for ~20% of total revenue |
| 🏷️ | Higher discounts drive increased sales volume in select categories |
| 📅 | Revenue fluctuates across months, indicating **possible seasonality** |

---

## 🖼️ Visualizations

Dashboard screenshots are available in the `/images` folder:

| File | Description |
|---|---|
| `dashboard_overview.png` | Full Power BI dashboard |
| `revenue_by_category.png` | Category-level revenue breakdown |
| `revenue_by_region.png` | Regional performance comparison |
| `monthly_trend.png` | Monthly revenue trend line |
| `payment_method_analysis.png` | Payment method distribution |

> Exported Power BI dashboard PDF is also included in the repository.

---

## 📁 Folder Structure

```
ecommerce-sales-analysis/
│
├── data/
│   ├── raw/
│   │   └── ecommerce_sales_raw.csv
│   └── cleaned/
│       └── ecommerce_sales_cleaned.csv
│
├── notebooks/
│   └── sales_analysis.ipynb
│
├── dashboard/
│   └── ecommerce_dashboard.pbix
│
├── images/
│   ├── dashboard_overview.png
│   ├── revenue_by_category.png
│   ├── revenue_by_region.png
│   ├── monthly_trend.png
│   └── payment_method_analysis.png
│
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

### Option 1 — Python (EDA & Cleaning)

```bash
# 1. Clone the repository
git clone https://github.com/your-username/ecommerce-sales-analysis.git

# 2. Navigate to the project directory
cd ecommerce-sales-analysis

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook notebooks/sales_analysis.ipynb
```

### Option 2 — Power BI Dashboard

1. Open `dashboard/ecommerce_dashboard.pbix` in Power BI Desktop
2. Refresh the dataset connection if prompted
3. Use the slicers to filter by **Region** and **Category**

---

## 🚀 Future Improvements

- [ ] Add **profit margin analysis** once cost data is available
- [ ] Build a **sales forecasting model** using time series (ARIMA / Prophet)
- [ ] Perform **customer segmentation** using K-Means clustering
- [ ] Deploy dashboard via **Power BI Service** for live sharing
- [ ] Automate the **ETL pipeline** for real-time data updates

---

## 📌 Conclusion

This project demonstrates a complete end-to-end data analytics workflow — from raw data cleaning to business insight generation — using industry-standard tools. It highlights the ability to translate data into strategic recommendations that support **revenue growth** and **operational decision-making**.

---

*Tools: Python • Power BI • DAX • Excel • Pandas • Matplotlib*
