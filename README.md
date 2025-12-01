# 📊 Sales Analysis & Performance Dashboard  
*A Complete Power BI Analytics Project (2017–2019)*

---
## 📁 Project Overview  
This project delivers a full **end-to-end sales intelligence dashboard** built in **Microsoft Power BI**.  
The goal was to turn raw sales data into **actionable financial, operational, and geographic insights**, helping decision-makers understand how the business performed over three years (2017–2019).

---
## 🗂️ Data Sources  
The analysis is based on four structured datasets:

- **📄 Sales Orders** — transaction details (dates, quantities, price, cost).  
- **👥 Customers** — customer profiles linked by ID.  
- **📦 Products** — product catalog linked by ID.  
- **🌍 Regions** — geographic mapping of suburbs & cities.
---

## 🔧 Data Transformation (Power Query)  
Extensive preprocessing and enrichment were performed using **Power Query**.

### ✔️ New Calculated Columns
- `Total Revenue = Order Quantity * Unit Selling Price`  
- `Total Cost = Order Quantity * Unit Cost`  
- `Total Profit = Total Revenue - Total Cost`  
- `Profit Margin = Total Profit / Total Revenue`  
- `Shipping Time (Days) = Ship Date - Order Date`

These transformations enabled deeper financial, operational, and logistical insights.

---

## 🧩 Data Modeling (Star Schema)  
A clean star schema was implemented:
### **⭐ Fact Table**
- Sales Orders
### **🔷 Dimension Tables**
- Customers  
- Products  
- Regions  
### **🔗 Relationships**
- All dimensions connected to the Sales Orders fact table via **one-to-many** relationships.

This ensures a high-performance, scalable BI model.

---

# 📊 Dashboard Structure
## 1️⃣ **📌 Introduction (Landing Page)**  
A clean, professional overview featuring:
- High-level KPIs  
- Navigation buttons  
- Overview of Total Revenue, Profit, Quantity & Customers

---

## 2️⃣ **💰 Financial Summary**  
A high-level executive analysis containing:
### **✔ DAX Measures**
- Total Revenue  
- Total Cost  
- Total Profit  

### **📈 Visuals**
- Revenue & Profit Trend (Line + Column combo)  
- Profit by Channel (Donut Chart)  
- Revenue by City & Top Customers (Bar Charts)

---

## 3️⃣ **🚚 Logistics & Profitability Analysis**
Focused on operational efficiency:
- **Shipping Time by City** (to identify bottlenecks)  
- **Most Profitable Products & Channels**  
- **Cost vs. Margin Breakdown**

---

## 4️⃣ **📦 Product & Regional Analysis**
Detailed product and location performance:
- **Treemap:** Top 10 Products by Revenue  
- **Map Visual:** Geographic revenue distribution

---

## 5️⃣ **📊 Advanced Analytics (R Visuals)**  
Integrated **R scripts** to perform deeper statistical analysis:
- **🎻 Violin Plot:** Profit distribution across channels  
- **📉 Frequency Polygon:** Profit per order distribution  
- **📌 Scatter + Trendline:** Cost vs. Revenue correlation  
- **🔷 Hexbin Heatmap:** Cost vs. Revenue density clusters  

---

## 6️⃣ **📈 Performance & Trend Analysis**
Seasonality, month-over-month changes, and profitability:
- **Matrix Heatmap** — Profit by Month & Year  
- **Gauge Chart** — Avg. Profit Margin vs. Target  

---

# 🧠 Key Insights  
### **✔ Financial Performance**
- Revenue exceeded **$21.4M**  
- Profit totaled **$7.1M**  
- Strong seasonal trends, especially in Q4  

### **✔ Sales Channels**
- **Wholesale** is the strongest revenue contributor  

### **✔ Products**
- Product **7** and **11** dominate revenue & profit  

### **✔ Geography**
- Major sales regions: **Auckland**, **Christchurch**, **Hamilton**  

### **✔ Operations**
- Significant variation in shipping times → opportunity for optimization  

---

# 🛠 Tools & Technologies  
- **Microsoft Power BI Desktop**  
- **Power Query**  
- **DAX (Data Analysis Expressions)**  
- **R (ggplot2, dplyr)**  

---

## 📎 Project Tags  
`#PowerBI` `#DataAnalysis` `#DataVisualization` `#R` `#Dashboard`  
`#BusinessIntelligence` `#Analytics` `#PowerQuery`  

---

## 📬 Connect With Me  
**LinkedIn:** www.linkedin.com/in/syedtasawarabbas  
**Email:** syed.tasawarabbas15@gmail.com  
