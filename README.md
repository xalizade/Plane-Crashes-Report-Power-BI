# Plane Crashes Report - Power BI Dashboard

## 📌 Overview
This project provides an interactive Power BI dashboard for analyzing aviation accidents, focusing on crash locations, causes, trends, and fatality data. It enables in-depth insights into aviation safety using structured datasets and advanced visualizations.

## 📂 Repository Structure
```
📁 xalizade/Plane-Crashes-Report-Power-BI
 ├── 📁 data excel/               # Contains raw and cleaned Excel datasets
 ├── 📄power_bi_files/            # Power BI (.pbix) reports
 ├── 📄 README.md                  # Project documentation (this file)
```

## 🚀 Features & Pages
The Power BI dashboard consists of multiple pages, each offering unique insights:

### **1️⃣ Aviation Safety Overview (Dashboard Summary)**
- 🛩️ Total Crashes, ☠️ Total Fatalities, 🎯 Survival Rate (KPI Cards)
- 📈 Line Chart: Crashes Over Time
- 🗺️ Heatmap: Crash Locations (Severity-Based)
- 🔍 Filters: Year, Aircraft Type, Operator
- 📝 Dynamic Summary Box (DAX-based auto-insights)

### **2️⃣ Trend Analysis (Crashes Over Time)**
- 📈 Yearly Crash Trend (Line Chart)
- 📊 Fatalities by Aircraft Type & Operator (Stacked Bar Chart)
- 📊 Monthly Crash Count (Column Chart)
- 🔍 Filters: Year, Operator, Aircraft Type

### **3️⃣ Geospatial Analysis (Crash Locations & Patterns)**
- 🗺️ Interactive Map (ArcGIS/Bing Maps) with crash severity color coding
- 📊 Bar Chart: Count of Crash by Countries 
- 🔍 Filters: Continent, Country, Year

### **4️⃣ Cause Analysis (Crash Causes & Insights)**
- 📝 Word Cloud:  Crash Causes
- 🥧 Pie Chart: Weather vs. Mechanical vs. Human Error
- 🔍 Filters: Year, Aircraft Type


## 🔄 Data Preparation (ETL - Extract, Transform, Load)
Before building the dashboard, data was cleaned and transformed:
- **Data Cleaning (Power Query)**
  - Missing values handled (Date, Time, Location, Fatalities)
  - Standardized Date Format (YYYY-MM-DD)
  - Split "Location" into City & Country
  - Consistent Operator Naming
- **Feature Engineering**
  - Extracted Year & Month for trend analysis
  - Categorized Crash Causes (Weather, Mechanical, Pilot Error, etc.)
  - Calculated Total Deaths & Survival Rate

## 🛠️ Technologies Used
- **Power BI** (Data visualization & analysis)
- **Excel** (Data storage & preprocessing)
- **DAX (Data Analysis Expressions)** (Dynamic measures & insights)
- **Power Query** (Data transformation)

## 📥 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/xalizade/Plane-Crashes-Report-Power-BI.git
   ```
2. Open Power BI and load the `.pbix` file.
3. Connect to the provided Excel datasets if needed.
4. Explore the interactive dashboard!

## 📧 Contact
For any questions or feedback, feel free to reach out:
**Khadija Alizada**
📧 Email: khadijaalizada222@gmail.com


