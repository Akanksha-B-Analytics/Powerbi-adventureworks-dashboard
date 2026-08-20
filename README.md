
# 📊 Power BI Dashboard – AdventureWorks Sales & Customer Analytics

## Project Overview

This project demonstrates the use of Power BI for building an interactive, multi-page business intelligence dashboard. Using the AdventureWorks dataset, the dashboard analyzes sales performance, customer behavior, and geographic distribution to support data-driven business decisions.

The project covers dashboard design, DAX measure creation, KPI tracking, what-if analysis, and interactive data visualization — core skills used by Business Intelligence and Data Analysts.

---

## Objectives

- Consolidate sales, customer, and product data into a single interactive dashboard.
- Track key business metrics (revenue, profit, orders, return rate) against targets.
- Enable dynamic what-if analysis for profit adjustment scenarios.
- Segment customers by income level and occupation to identify high-value groups.
- Visualize geographic sales distribution across regions and countries.

---

## Tools & Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling
- Interactive Visualizations & Filters

---

## Project Structure

```
powerbi-adventureworks-dashboard/
│
 dashboard/
│   └── AdventureWorks_Dashboard.pbix

 screenshots/
│    01_executive_summary.png
│    02_product_performance.png
│    03_customer_segmentation.png
│    04_geographic_analysis.png
│
├── docs/
│   └── dax_measures.md
│
├── README.md
└── LICENSE
```

---

## Dashboard Pages

### 1. Executive Summary
- Tracks headline metrics: $24.9M revenue, $10.5M profit, 25.2K total orders, and a 2.2% return rate.
- Weekly revenue trend with confidence band to visualize momentum over time.
- Order breakdown by category (Accessories, Bikes, Clothing) and a Top 10 Products table by orders, revenue, and return %.
- Surfaces "Tires and Tubes" as the most-ordered product type and "Shorts" as the most-returned.

### 2. Product Performance & What-If Analysis
- KPI gauge visuals comparing total order, revenue, and profit against target for a selected product.
- Interactive "Profit Adjustment" slider built using a DAX what-if parameter to simulate margin changes on adjusted profit in real time.
- Trend chart comparing actual vs. adjusted profit by day of week.
- Auto-generated report summary text highlighting best/worst performing days.

### 3. Customer Segmentation
- Summarizes 17.4K unique customers and average revenue per customer.
- Donut charts segmenting orders by income level and occupation.
- Top 100 Customers table ranked by revenue.
- Time-based revenue-per-customer trend across 2020–2022.

### 4. Geographic Analysis
- Interactive map visual plotting total orders by country (US, UK, Canada, Germany, France, Australia).
- Region-based filter panel (Europe, North America, Pacific).
- Bubble sizing reflects relative order volume across markets.

---

## Key Skills Demonstrated

- Power BI Dashboard Design
- DAX (Calculated Columns, Measures, What-If Parameters)
- Data Modeling
- KPI Tracking & Target Analysis
- Customer Segmentation
- Geographic Data Visualization
- Business Reporting & Insight Generation

---

## Learning Outcomes

Through this project, I strengthened my ability to design interactive, multi-page dashboards in Power BI, write DAX measures for dynamic analysis, and translate raw business data into clear, decision-ready visual insights applicable to real-world Data Analyst roles.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## About Me

Hey!! I am **Akanksha Borkar**
Aspiring Data Analyst | SQL | Power BI | Data Analytics
