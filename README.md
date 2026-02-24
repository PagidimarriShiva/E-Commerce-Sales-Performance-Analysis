# 📊 E-Commerce Sales Performance Analysis

## 📌 Project Overview
This project analyzes e-commerce transactional data to uncover revenue trends, regional performance, product category insights, and customer purchasing behavior. The goal was to transform raw sales data into actionable business insights using data cleaning, exploratory analysis, and interactive visualization techniques.

The final output includes KPI analysis and a Power BI dashboard to support data-driven decision-making.

---

## 🎯 Problem Statement
The business wanted to understand:

- Which product categories drive the most revenue?
- Which regions contribute the highest sales?
- How do discounts impact quantity sold?
- Which payment methods are most preferred?
- What insights can improve revenue and customer satisfaction?

This project answers these questions using structured data analysis.

---

## 📂 Dataset Information

The dataset contains transactional e-commerce data including:

- Order ID  
- Order Date  
- Product Category  
- Price  
- Discount Percentage  
- Quantity Sold  
- Customer Region  
- Payment Method  
- Rating  
- Review Count  
- Discounted Price  
- Total Revenue  

### Dataset Summary:
- Total Revenue: **32,866,573.74**
- Total Quantity Sold: **149,970 units**
- Multiple regions and product categories analyzed

---

## 🛠 Tools & Technologies Used

- **Power BI** – Dashboard creation & visualization  
- **DAX** – KPI measures and calculated metrics  
- **Python (Pandas, Matplotlib)** – Data cleaning & exploratory analysis  
- **Excel** – Initial data validation  

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Checked for missing values and duplicates  
- Validated discounted price calculations  
- Verified total revenue formula  
- Standardized date formats  

### 2️⃣ Exploratory Data Analysis (EDA)
- Revenue by product category  
- Revenue by region  
- Revenue by payment method  
- Monthly revenue trends  
- Discount vs quantity correlation  

### 3️⃣ Business Analysis
- Calculated KPIs:
  - Total Revenue  
  - Total Orders  
  - Average Order Value (AOV)  
  - Revenue Contribution %  
- Identified top-performing regions and categories  
- Analyzed impact of discount strategy  

### 4️⃣ Visualization
- Built interactive Power BI dashboard  
- Created bar charts, line charts, and KPI cards  
- Implemented filters for region and category analysis  

### 5️⃣ Insights Generation
- Translated analysis into business recommendations  
- Highlighted revenue concentration risks  
- Identified growth opportunities  

---

## 📈 Key Findings

- Middle East contributes ~25% of total revenue (top-performing region)
- Beauty category contributes ~17% of total revenue
- Wallet payments account for ~20% of revenue
- Higher discounts increase sales volume in select categories
- Revenue shows fluctuations across months indicating possible seasonality

---

## 🖼 Visualizations

Dashboard screenshots are available in the `/images` folder:

- `revenue_by_category.png`
- `revenue_by_region.png`
- `monthly_trend.png`
- `payment_method_analysis.png`
- `dashboard_overview.png`

(Exported Power BI dashboard PDF also included in repository.)

---

## 📁 Folder Structure

---

## ▶️ How to Run the Project

### Option 1: Using Python (EDA)

1. Clone the repository:
2. Navigate to project directory:
3. Install dependencies:
4. Run Jupyter Notebook:

Open `sales_analysis.ipynb` to view full analysis.

---

### Option 2: Using Power BI

1. Open `ecommerce_dashboard.pbix`
2. Refresh dataset connection if needed
3. Explore interactive filters and KPIs

---

## 🚀 Future Improvements

- Add profit margin analysis (if cost data becomes available)
- Implement sales forecasting using time series modeling
- Perform customer segmentation using clustering
- Deploy interactive dashboard via Power BI Service
- Automate ETL pipeline for real-time updates

---

## 📌 Conclusion

This project demonstrates end-to-end data analysis — from raw data cleaning to business insight generation — using industry-standard tools. It highlights the ability to transform data into strategic recommendations that support revenue growth and operational decision-making.
