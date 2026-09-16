# Inventory Optimization Dashboard

## Project Overview

This project analyzes inventory performance and warehouse operations to identify opportunities for reducing carrying costs, improving inventory turnover, and minimizing stockouts.

The dashboard provides actionable insights for supply chain and logistics teams by tracking key inventory management KPIs and highlighting slow-moving inventory.

---

## Business Problem

Organizations often struggle with:

- Excess inventory
- Stockouts
- Low inventory turnover
- Aging inventory
- Poor warehouse space utilization

The goal of this project is to use data analytics to improve inventory decision-making and optimize stock levels.

---

## Objectives

- Analyze inventory performance
- Identify slow-moving products
- Monitor inventory aging
- Measure inventory turnover
- Create reorder recommendations
- Build an interactive business dashboard

---

## Tools Used

- Python
- Pandas
- SQL
- Power BI
- GitHub

---

## Project Structure

inventory-optimization-dashboard/

├── data/

│ ├── raw/

│ └── cleaned/

├── notebooks/

│ └── inventory_analysis.ipynb

├── sql/

│ └── inventory_queries.sql

├── dashboard/

│ └── inventory_dashboard.pbix

├── images/

│ └── dashboard_overview.png

├── README.md

└── requirements.txt

---

## Key Metrics

### Inventory Turnover

Measures how efficiently inventory is sold and replaced.

### Days Inventory Outstanding (DIO)

Measures how long inventory remains in storage before being sold.

### Stockout Rate

Percentage of orders that could not be fulfilled due to lack of inventory.

### Fill Rate

Percentage of customer demand fulfilled immediately from available inventory.

### Aging Inventory

Tracks inventory held longer than:

- 90 Days
- 180 Days
- 365 Days

---

## Analysis Process

### Data Cleaning

- Removed duplicates
- Standardized product categories
- Corrected missing values
- Validated inventory quantities

### SQL Analysis

- Inventory by category
- Slow-moving products
- Inventory aging reports
- Supplier performance analysis

### Python Analysis

- KPI calculations
- Inventory turnover analysis
- Demand trend analysis
- Reorder point recommendations

### Dashboard Development

Created interactive Power BI visualizations including:

- Inventory Value Overview
- Aging Inventory Analysis
- Warehouse Utilization
- Supplier Performance
- Reorder Recommendations

---

## Key Findings

Example findings:

- 28% of inventory value is tied to products older than 180 days
- Category B inventory turnover is significantly lower than average
- Several products consistently experience stockout events

---

## Recommendations

- Implement automated reorder thresholds
- Reduce stock levels of slow-moving products
- Improve supplier lead time monitoring
- Strengthen FIFO inventory practices
- Increase visibility into aging inventory

---

## Future Enhancements

- Forecast demand using machine learning
- Safety stock optimization
- ABC inventory classification
- Automated supplier scorecards

---

## Author

Nichelle Outlaw

Supply Chain & Logistics Professional

LinkedIn: www.linkedin.com/in/nichelle-outlaw
