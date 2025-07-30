# Sales-Performance-dashboard
# 📊 Sales Dashboard – Excel + DAX

This repository contains an interactive Excel-based sales dashboard built using Pivot Tables, Slicers, and DAX. The project summarizes sales data with key KPIs and visuals, ideal for showcasing Excel analytics skills.

---

## 📁 File Included

- `Sales_Dashboard.xlsx` – Excel file with dashboard visuals and DAX-driven KPI summary cards.

---

## 🚀 Dashboard Highlights

- 📌 Pivot Tables for product/category/region sales breakdown
- 🎚️ Slicers for dynamic filtering
- 🧾 Summary KPI Cards with DAX measures
- 📈 Charts for category and regional sales insights

---

## 🧠 DAX Measures Used (for KPI Cards)

The following DAX measures were used in Power Pivot to calculate the summary cards:

| KPI 📌                     | DAX Measure                                                                 |
|----------------------------|------------------------------------------------------------------------------|
| 💰 **Total Sales**         | `Total Sales := SUM(Sales[SalesAmount])`                                    |
| 📦 **Total Orders**        | `Total Orders := DISTINCTCOUNT(Sales[OrderID])`                             |
| 📊 **Total Units Sold**    | `Total Units Sold := SUM(Sales[Quantity])`                                  |
| 📈 **Average Sales/Order** | `Average Sales := DIVIDE([Total Sales], [Total Orders], 0)`                 |

> All KPIs are dynamically updated based on slicer selections.

---

## 🧰 Tools & Techniques Used

- Microsoft Excel  
- Pivot Tables & Charts  
- Slicers  
- Power Pivot  
- DAX (Data Analysis Expressions)  
- Summary Cards (KPI)  
- Clean Dashboard Formatting


## 📈 How to Use

1. Open the Excel file in **Excel 2016 or later** (with Power Pivot enabled).
2. Use the slicers to explore sales performance by region or product.
3. KPI cards and charts update automatically.

---

## 👩‍💼 Author

**Keerthana Veldanda**  
[LinkedIn](https://www.linkedin.com/in/veldanda-keerthana-496b9834a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

