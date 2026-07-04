# 📊 Sales & Revenue Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Project-black?style=for-the-badge&logo=github)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

# 📌 Project Overview

The **Sales & Revenue Analysis Dashboard** is an interactive business intelligence dashboard developed using **Microsoft Power BI**. It transforms raw sales data into meaningful business insights through KPIs, interactive charts, and dynamic filters, helping organizations monitor performance and make data-driven decisions.

---

# 🎯 Objectives

- Analyze sales and revenue performance.
- Track key business KPIs.
- Monitor revenue trends over time.
- Identify top-performing categories.
- Compare sales across different countries.
- Enable interactive dashboard filtering.

---

# 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset
- GitHub

---

# 📂 Project Files

```text
Sales-Revenue-Analysis-Dashboard
│
├── Sales_Revenue_Analysis_Dashboard.pbix
├── sales_data.csv
├── dashboard.png
└── README.md
```

---

# 📊 Dashboard Features

### KPI Cards

- 💰 Total Revenue
- 💸 Total Cost
- 📈 Profit
- 📦 Total Orders

### Visualizations

- 📈 Revenue Trend (Line Chart)
- 📊 Revenue by Category (Column Chart)
- 🥧 Revenue by Country (Pie Chart)
- 📉 Revenue by Device Type (Bar Chart)

### Interactive Slicers

- 🌍 Country
- 🗂️ Category
- 💻 Device Type
- 👨‍💼 Sales Manager

---

# 📷 Dashboard Preview

> Replace this image with your own dashboard screenshot.

![Dashboard](dashboard.png)

---

# 📐 DAX Measures

### Total Revenue

```DAX
Total Revenue =
SUM(Sales_data[order_value_EUR])
```

### Total Cost

```DAX
Total Cost =
SUM(Sales_data[cost])
```

### Profit

```DAX
Profit =
[Total Revenue] - [Total Cost]
```

### Total Orders

```DAX
Total Orders =
COUNT(Sales_data[order_id])
```

---

# 📈 Business Insights

This dashboard helps identify:

- Revenue trends over time.
- High-performing product categories.
- Country-wise revenue distribution.
- Device-wise sales performance.
- Sales manager performance.
- Overall business performance using KPIs.

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Power Query
- DAX Calculations
- KPI Development
- Dashboard Design
- Data Visualization
- Business Intelligence
- Interactive Reporting

---

# 📄 Dataset

The dataset includes:

- Order ID
- Date
- Country
- Category
- Customer Name
- Sales Manager
- Sales Representative
- Device Type
- Order Value (EUR)
- Cost

---

# 🔮 Future Enhancements

- Profit Margin Analysis
- Sales Forecasting
- Customer Segmentation
- Drill-through Reports
- Dynamic Tooltips
- Mobile Dashboard Layout
- Row-Level Security (RLS)

---

# 👨‍💻 Author

**Pathan Laharin**

Computer Science & Engineering Student

Aspiring **Data Analyst | Business Intelligence Enthusiast | AI Learner**

Passionate about transforming raw data into actionable insights through analytics and visualization.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
