# 🚗 Car Showroom Analysis - Power BI & Python ETL Project

## 📌 Project Overview
This project simulates an analytics task for a car showroom company ("Hot Wheels") using real-world ETL and dashboard reporting. Python is used for cleaning and transforming raw data, and Power BI is used to build insightful dashboards.

## 🧹 ETL Tasks (Python)
- Cleaned phone numbers (removed special characters)
- Merged employee and customer datasets
- Added FullName column
- Calculated NewPrice (3% hike)
- Split CarModel from CarName
- Calculated BillAmount with tax and discount
- Exported final output to Excel

## 📊 Power BI Dashboard
- Visualized Booking Data, Revenue, Discounts, Car Models
- Slicers for filtering data
- KPI cards for high-level insights

## 📁 Folder Structure
- `data/` – Source files
- `ETL_Car_Showroom.ipynb` – Data processing in Python
- `dashboard/` – Power BI file (.pbix)
- `output/` – Final Excel used in Power BI
- `assets/` – [Screenshots of dashboard](https://github.com/yusufonline98/Car-Showroom-Analysis---Power-BI-Python-ETL-Project/blob/main/Powerbi_car_showroom_dashboard.png)

## 🛠 Tools Used
- Python (Jupyter Notebook via Anaconda)
- Pandas, NumPy
- Power BI
