# 📊 Superstore Sales — Tableau Dashboard

An interactive Tableau dashboard to analyze sales performance, track KPIs, and generate actionable insights for stakeholders.

---

## 📌 Project Overview

This project analyzes superstore sales data using **Tableau Desktop** to build an interactive dashboard with meaningful business insights across regions, customers, and time periods.

---

## 🎯 Objectives

- Track KPIs like Revenue, Profit, and Order Quantity
- Analyze regional and customer segment performance
- Visualize sales trends over time
- Enable data-driven decision-making through interactivity

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Tableau Desktop 2025.2 | Dashboard creation & visualization |
| Tableau Calculated Fields | Custom segmentation logic |
| Sample Superstore Sales (Excel) | Primary data source |
| GitHub | Version control & project hosting |

---

## 📂 Dataset

| Field | Description |
|---|---|
| Region | Geographic region of the sale |
| Customer Segment | Customer category (Consumer, Corporate, etc.) |
| Customer Name | Individual customer identifier |
| Order Date | Date the order was placed |
| Sales | Total sales amount |
| Profit | Profit earned per transaction |
| Order Quantity | Number of units ordered |
| Unit Price | Price per unit sold |

---

## 🔄 Data Processing

✅ Connected to Sample Superstore Sales Excel via federated connection  
✅ Created a custom calculated field for price-tier segmentation  
✅ Structured Dimensions vs. Measures for accurate aggregation  
✅ Configured cross-sheet action filters for dynamic interactivity  

**Calculated Field — Grouping By Unit Price:**
```
IF [Unit Price] <= 2500 THEN "A"
ELSEIF [Unit Price] <= 5000 THEN "B"
ELSE "C"
END
```

---

## 📊 Dashboard Pages

### Dashboard 1 — Overview
High-level executive summary layout *(650 × 860 px, fixed)*.

### Dashboard 2 — Detailed Analysis
Full interactive dashboard combining all four views.

| Chart | Description |
|---|---|
| Bar Chart | Profits by Region and Customer Segment |
| Line Chart | Order Quantity trends by Month |
| Pie Chart | % Sales Contribution by Region |
| Scatter Plot | Sales vs. Profit by Customer |

> Click any chart to filter all other views. Click an empty area to clear.

---

## 📐 Key Measures

| Measure | Description |
|---|---|
| SUM(Profit) | Total profit across selected filters |
| SUM(Sales) | Total revenue across selected filters |
| SUM(Order Quantity) | Total units ordered |
| % of Total Sales | Each region's share of overall sales |
| Grouping By Unit Price | A / B / C price-tier segmentation |

---

## 💡 Key Insights

- 📍 Compare **regional profit** across segments via the Bar Chart
- 🥧 Spot **top revenue regions** through the Pie Chart
- 📈 Track **monthly demand patterns** in the Line Chart
- 🔵 Identify **high-profit vs. loss-making customers** in the Scatter Plot
- 🎯 Segment data by **price tier (A/B/C)** for targeted analysis

---

## 👨‍💻 Author

**Sandeep**  
Data Analytics | Tableau | SQL | Python | Business Intelligence
