# Renewable-Energy-Generation-Dashboard-India-mini-project
# 🌱 Renewable Energy Generation Dashboard (India)

## 📌 Project Overview

This project analyzes renewable energy generation across India from **2020 to 2025** using **Excel** and **Power BI**. The objective is to clean and transform the dataset, build an efficient data model, create DAX measures, and develop an interactive dashboard that provides meaningful insights into renewable energy production across different states and regions.

---

## 🎯 Objectives

- Clean and transform raw renewable energy data.
- Perform data analysis using Excel Pivot Tables.
- Build a star schema data model in Power BI.
- Create DAX measures for key performance indicators.
- Develop an interactive dashboard using Power BI.
- Visualize renewable energy trends across India.

---

## 📂 Repository Contents

```
📁 Renewable-Energy-Dashboard
│
├── Raw_Excel_File.xlsx
├── Cleaned_Excel_File.xlsx
├── Renewable_Energy_Dashboard.pbix
├── Renewable_Energy_Project_Documentation.pdf
├── Dashboard_Screenshot.png
└── README.md
```

---

## 📊 Dataset Information

The dataset contains renewable energy generation data for Indian states from **2020 to 2025**.

### Dataset Columns

- ID
- Date
- State Name
- State Code
- Region
- Wind Energy
- Solar Energy
- Other Renewable Energy
- Total Renewable Energy

### Created Columns

- Year
- Month
- Month Number
- Energy Category
- Dominant Energy Source

---

## 🛠️ Tools & Technologies Used

- Microsoft Excel
- Pivot Tables
- Power Query
- Microsoft Power BI
- DAX
- Data Modeling
- GitHub

---

## 🧹 Data Cleaning & Transformation

The following preprocessing steps were completed:

- Removed duplicate records
- Checked and handled missing values
- Standardized data formats
- Converted Date column into Date format
- Created Year and Month columns
- Added Month Number column
- Created Energy Category column
- Created Dominant Energy Source column
- Verified numerical columns
- Built Pivot Tables for summary analysis

---

## ⭐ Data Model

A Star Schema data model was created with:

### Fact Table

- RenewableData

### Dimension Tables

- Dim_State
- Dim_Region
- Dim_Year

Relationships were created using one-to-many cardinality.

---

## 📈 DAX Measures

The following measures were created:

- Total Renewable Energy
- Total Wind Energy
- Total Solar Energy
- Total Other Renewable Energy
- Average Renewable Energy
- Maximum Renewable Energy
- Minimum Renewable Energy
- Total States
- Total Regions

---

## 📊 Dashboard Features

### KPI Cards

- Total Renewable Energy
- Total Wind Energy
- Total Solar Energy
- Total Other Energy
- States Covered
- Regions Covered

### Interactive Filters

- Region
- Energy Category
- Year
- State

### Visualizations

- Top 10 States by Renewable Energy
- Renewable Energy Trend by Year
- Renewable Energy Distribution by Region (Pie Chart)
- Renewable Energy by Region (Bar Chart)
- Renewable Energy by State (Map)

### Additional Features

- Clear Filters Button
- Interactive Slicers
- Dynamic Filtering
- Clean Dashboard Layout

---

## 🔍 Key Findings

- Total Renewable Energy generated exceeded **1.24 Million Units**.
- Wind and Solar Energy contribute the largest share of renewable generation.
- National Region contributes the highest renewable energy generation.
- Renewable energy generation shows strong growth during 2020–2024.
- The dashboard enables quick comparison of renewable energy production across Indian states and regions.

---

## 📷 Dashboard Screenshot
---

<img width="877" height="493" alt="Screenshot 2026-07-22 234858" src="https://github.com/user-attachments/assets/86037000-e59d-4ad7-8f6d-5961da786176" />

---

## 🚀 Future Improvements

- Add Tooltip Pages
- Drill-through Reports
- Forecasting Visuals
- Mobile Layout
- Dynamic Theme Switching

---

## 👨‍💻 Author

**Subramaniyam R**

Data Analytics Mini Project

Power BI | Excel | DAX | Data Visualization

---
