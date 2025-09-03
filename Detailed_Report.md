# 🛒 Supermarket Sales Dashboard – Excel Project

An interactive Excel dashboard analyzing supermarket sales data.  
This project demonstrates **data cleaning, KPI creation, PivotTables, and dashboard design** for data analysis.

---

## 📊 Dataset
- **Source**: [Kaggle – Supermarket Sales](https://www.kaggle.com/)  
- **Size**: 1,000 sales transactions  
- **Columns**: Sale ID, City, Branch, Customer Type, Gender, Product, Category, Unit Price, Quantity, Tax, Total Price, Reward Points

---

## 🛠️ Steps Performed

### 1. Data Cleaning
- Removed duplicates and blanks  
- Standardized text fields with **TRIM / CLEAN**  
- Converted numbers stored as text → numeric format  
- Created helper columns (Month, Weekday)  
- Checked for invalid values (negative or zero quantities)

### 2. KPIs
- **Total Revenue**: \$118,583.90  
- **Total Orders (distinct)**: 1,000  
- **Average Order Value (AOV)**: \$118.58  
- **Average Basket Size (per order)**: 10.34 items  
- **Net Revenue (ex-tax)**: \$110,825.89  
- **Effective Tax % (on net)**: 7.00%  
- **Reward Points Issued**: 6,057  

### 3. Analysis with PivotTables
- Revenue by City  
- Revenue by Product Category  
- Revenue by Gender  
- AOV by Customer Type  
- Top 5 Products by Revenue  
- Reward Points by City  

### 4. Dashboard Design
- KPI cards on top (linked via `GETPIVOTDATA`)  
- Slicers for **City**, **Customer Type**, **Product Category**  
- PivotCharts for revenue trends and comparisons  
- Clean, professional layout with consistent number formats  

---

## 📈 Dashboard Preview
 ![Dashboard Screenshot](Screenshot%20SalesDashboard.png) 

---

## 🔑 Key Insights
- **Chicago** generates the highest revenue (~\$42.6k).  
- **Members** spend more per order than **Normal** customers.  
- **Personal Care** and **Fruits** categories contribute the most revenue.  
- **Shampoo, Notebook, and Orange Juice** are top-selling products.  
- Effective tax rate is **~7%**, reducing gross revenue by ~\$7.7k.  

---

## 🚀 How to Use
1. Download `Supermarket_Sales_Dashboard.xlsx` from this repo.  
2. Open in Excel → go to **Dashboard** sheet.  
3. Use slicers (City, Customer Type, Product Category) to filter results.  
4. KPIs and charts auto-update with filters.  

---

## 🙌 Inspiration & Credits  
- Dataset from Kaggle.  
- All cleaning steps, KPIs, and design customizations done by me.
