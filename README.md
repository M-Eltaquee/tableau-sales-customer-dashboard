# 📊 Sales & Customer Performance Dashboard – Tableau

### 🔗 [My LinkedIn](https://www.linkedin.com/in/your-profile/)
### 📥 [Download the Tableau Workbook](https://github.com/M-Eltaquee/tableau-sales-customer-dashboard/blob/main/assets/SalesCustomer.twbx?raw=true)
### 📊 [View on Tableau Public](#)
**📄 [Full Documentation](https://htmlpreview.github.io/?https://github.com/M-Eltaquee/tableau-sales-customer-dashboard/blob/main/PROJECT-DOCUMENTATION.html)**

<br>
<div align="center">
  <img src="https://github.com/M-Eltaquee/tableau-sales-customer-dashboard/blob/main/assets/demo.gif?raw=true" alt="Sales & Customer Dashboard Demo" width="1000">
</div>

---

## 📝 Introduction
<details>
  <summary><strong>📌 Overview (click)</strong></summary>

### **Overview**
> This Tableau project analyzes sales performance and customer behavior using two connected dashboards. The Sales Dashboard tracks total sales, profit, and quantity trends year-over-year, while the Customer Dashboard examines customer distribution, order frequency, and top-performing accounts by profit.

</details>

<details>
  <summary><strong>📂 Data Sources (click)</strong></summary>

### **Data Sources**
> Superstore-style retail dataset covering orders, products, customers, and sales/profit figures across multiple years.

**▼ 📑 Dataset Explanation**
1. **Orders Table**
   - `Order ID`, `Order Date`, `Ship Date`, `Customer ID`, `Product ID`, `Sales`, `Profit`, `Quantity`
2. **Customer Table**
   - `Customer ID`, `Customer Name`, `Segment`
3. **Product Table**
   - `Product ID`, `Category`, `Sub-Category`

</details>

---

## 🎯 Case Study
Sales managers and executives needed a clear year-over-year view of sales performance, while marketing and management needed visibility into customer behavior and segmentation. Two dashboards were built to serve both audiences:
- Track KPI performance for current year vs. previous year
- Identify high and low performing months
- Compare subcategory performance
- Understand customer order distribution and identify top-value customers

---

## 📊 Main KPIs
- **💰 Total Sales**: current year vs. previous year, with % variance
- **📈 Total Profit**: current year vs. previous year, with % variance
- **📦 Total Quantity**: current year vs. previous year, with % variance
- **👥 Total Customers / Sales per Customer**: current year vs. previous year
- **🧾 Total Orders**: current year vs. previous year

---

## ⚙️ Process
1. Defined the user story and requirements for both dashboards
2. Sketched dashboard mockups in Excalidraw before building
3. Built a dynamic Select Year parameter to drive current-year and last-year comparisons
4. Created calculated fields for CY/LY sales, profit, and quantity
5. Built monthly and weekly trend views with highlighted highest/lowest points
6. Designed a bar-in-bar chart to compare sales and profit by subcategory
7. Built the Customer Dashboard with order distribution and Top 10 Customers by Profit
8. Added interactive filters (Category, Sub-Category, Region, State, City) and dashboard navigation

---

## 📈 Dashboard Preview
<img src="https://github.com/M-Eltaquee/tableau-sales-customer-dashboard/blob/main/assets/sales-dashboard-page.png?raw=true" width="1000">
<img src="https://github.com/M-Eltaquee/tableau-sales-customer-dashboard/blob/main/assets/customer-dashboard-page.png?raw=true" width="1000">

---

## 🔍 Key Insights
Full breakdowns of sales trends, subcategory performance, customer distribution, and top-value customers are visible directly in the dashboard screenshots above.

---

## 💡 Conclusion
This Tableau project gives sales and marketing teams a clear, interactive view of year-over-year performance and customer value, helping identify where to focus commercial attention.

---

## 🧰 Tools Used
- **Tableau Desktop**
- **Tableau Calculated Fields & Parameters**
- **Excalidraw** (mockup design)

---
## 📁 Project Structure

```bash
tableau-sales-customer-dashboard/
│
├── assets/
│   ├── sales-dashboard-page.png
│   ├── customer-dashboard-page.png
│   ├── demo.gif
│   ├── layout.png
│   ├── requirements.png
│   ├── top-10-customers.png
│   ├── total-customer-card.png
│   ├── total-orders-card.png
│   ├── total-sales-card.png
│   ├── weekly-trends.png
│   └── SalesCustomer.twbx
│
└── README.md
```
