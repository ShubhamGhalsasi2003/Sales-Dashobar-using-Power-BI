# 📊 Power BI Sales Dashboard – Nike Dataset

An interactive Power BI dashboard analyzing Nike’s sales performance across regions, time, and product categories.  
This project was created as part of my journey to learn and showcase **Data Visualization & Business Intelligence** using **Power BI**.  

---

![Power BI](https://img.shields.io/badge/Tool-PowerBI-yellow) 
![Excel](https://img.shields.io/badge/Data-Excel-green) 
![Status](https://img.shields.io/badge/Status-Completed-blue)

---

## 📁 Dataset
- **Source:** [Kaggle – Nike Sales Data](https://www.kaggle.com/)  
- **Format:** Excel (`Nike-Sales-Dataset.xlsx`)  
- **Contents:**  
  - Sales & Revenue values  
  - Product Categories (Shoes, Apparel, Accessories)  
  - Regional data (North America, Europe, Asia, etc.)  
  - Date-wise transactions  

---

## 🔍 Key Features
- 📈 **Revenue Trend Analysis** – Sales and revenue over time  
- 🌍 **Region-wise Performance** – Map view of sales across different geographies  
- 👟 **Top-selling Products** – Categories & subcategories with highest revenue  
- 🎛 **Interactive Filters** – Dynamic slicers for year, product category, and region  
- 📊 **KPIs** – Total Sales, Revenue, Profit, and Growth Rate  

---

## 💡 Tools Used
- **Microsoft Power BI Desktop** – Dashboard development  
- **Power Query Editor** – Data cleaning & transformation  
- **DAX (Data Analysis Expressions)** – Custom measures and KPIs  
- **Excel** – Raw dataset  

---

## 🛠️ Implementation Steps

1. **Data Collection**
   - Downloaded the Nike Sales dataset from Kaggle (`Nike-Sales-Dataset.xlsx`).  

2. **Data Import**
   - Imported the Excel file into **Power BI Desktop**.  
   - Verified and assigned correct data types (date, number, text).  

3. **Data Cleaning & Transformation (Power Query)**
   - Removed nulls & duplicates.  
   - Standardized product names and regions.  
   - Created a proper date table for time-based analysis.  

4. **Data Modeling**
   - Built relationships between fact (sales) and dimension (product, region, date) tables.  
   - Ensured a star schema for efficient reporting.  

5. **Calculated Measures (DAX)**
   - `Total Sales = SUM(Sales[Quantity])`  
   - `Total Revenue = SUM(Sales[Revenue])`  
   - `Profit Margin = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Revenue]))`  
   - YTD and Month-over-Month growth using `DATESYTD` and `SAMEPERIODLASTYEAR`.  

6. **Dashboard Design**
   - KPI Cards for Sales, Revenue, Profit.  
   - Line chart for revenue trend.  
   - Map visualization for regional sales.  
   - Bar chart for best-selling categories.  
   - Slicers for dynamic filtering.  

7. **Formatting & Customization**
   - Applied **Nike-inspired theme** (black, red, white).  
   - Added titles, labels, and tooltips.  
   - Optimized layout for readability and interactivity.  

8. **Export & Sharing**
   - Exported `.pbix` file.  
   - Recorded demo walkthrough (`Dashboard.mp4`).  
   - Documented project in this `README.md`.  

---

##  Screenshots
- 📸 **Dashboard Preview:**  
  <img width="1920" height="1080" alt="Screenshot From 2025-08-19 15-11-19" src="https://github.com/user-attachments/assets/9968ca52-5237-466a-8455-dc77b46e4b43" />
<img width="1920" height="1080" alt="Screenshot From 2025-08-19 15-11-30" src="https://github.com/user-attachments/assets/34000d57-89c0-48ed-b74a-2c4d95a50637" />
<img width="1920" height="1080" alt="Screenshot From 2025-08-19 15-11-47" src="https://github.com/user-attachments/assets/2b3e9818-540d-47d8-a8a8-6e8fb0a38b6a" />
<img width="1920" height="1080" alt="Screenshot From 2025-08-19 15-12-00" src="https://github.com/user-attachments/assets/63c85679-5515-4cf8-b2d0-d25528c5c777" />



## 🚀 How to Use
2. Open the `Nike-Sales-Dataset.xlsx` file to view raw data.  
3. Open the `Dashboard.pbix` file in **Microsoft Power BI Desktop**.  
4. Explore the dashboard with interactive filters.  

---

## 📈 Results & Insights
- Footwear category contributed the **highest revenue share**.  
- **North America** emerged as the top-performing region.  
- Sales showed **consistent growth** over multiple years.  
- Seasonal peaks observed during **Q4 (holiday season)**.  

---


## 👨‍💻 Author
**Shubham Ghalsasi**  
- 🌐 [GitHub Profile](https://github.com/)  
- 💼 [LinkedIn Profile](https://linkedin.com/)  
