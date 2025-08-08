# 🚗 Car Showroom Analysis - Power BI & Python ETL Project

## 📌 Project Overview
This project simulates an analytics task for a car showroom company using real-world ETL and dashboard reporting. It covers the **full data pipeline** — from cleaning and transforming raw CSV files with Python to creating an **interactive Power BI dashboard** that visualizes sales, pricing, and customer insights.

## 🎯 Business Problem
Hot Wheels had multiple CSV files with:
- Inconsistent formats
- Missing fields
- Price data without adjustments
- Discount rules not applied

The goal was to:
1. **Consolidate** all data into one clean dataset.
2. **Apply business logic** (price hike, tax, discounts).
3. **Create a dashboard** for quick decision-making.

---

## 🔧 Tools & Technologies
- **Python** (Jupyter Notebook via Anaconda)
  - pandas, numpy, openpyxl
- **Power BI Desktop**
- **Microsoft Excel**

## 🧹 ETL Tasks (Python)
- Cleaned phone numbers (removed special characters)
- Merged employee and customer datasets
- Added FullName column
- Calculated NewPrice (3% hike)
- Split CarModel from CarName
- Calculated BillAmount with tax and discount
- Exported final output to Excel

## 📊 Power BI Dashboard

### **Key Visuals**
- **KPI Cards** → Total Revenue, Total Cars Sold, Avg Price per Model
- **Bar Chart** → Sales by CarModel
- **Pie Chart** → Distribution of Car Models
- **Table** → Customer-level Bill Amount
- **Slicers** → CarModel, CustomerName, BookingID

### **Interactive Features**
- Drill-through on Customer → See all bookings for that customer
- Tooltips showing old price vs. new price and discount applied

## 📁 Folder Structure
- `ETL_Car_Showroom.ipynb` – Data processing in Python
- `dashboard/` – [power bi.pbix](https://github.com/yusufonline98/Car-Showroom-Analysis---Power-BI-Python-ETL-Project/blob/main/power%20bi.pbix)
- `assets/` – <img width="1276" height="665" alt="Powerbi_car_showroom_dashboard" src="https://github.com/user-attachments/assets/623ecbd2-78f4-4cb3-ae6d-a223e4734e90" />

