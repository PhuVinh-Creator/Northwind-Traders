# Northwind-Traders-Logistics
Power BI Dashboard Shipment Analysis

## Overview 📋

This project presents an interactive business intelligence dashboard built for **NorthWind**, covering two core analytical views: **Sales Analysis** and **Shipment Analysis**. The dashboards provide a comprehensive overview of the company's sales performance and logistics efficiency across multiple time periods, regions, and customer segments.

---

## Dashboard Views 🖥️

### 1. Sales Analysis
Tracks overall revenue performance and employee contribution across the organization.

**Key Metrics:**
- **Revenue:** $1.27M
- **AOV (Average Order Value):** $1.53K
- **Revenue YTD:** 53.40%
- **Number of Orders:** 830
- **Revenue YoY%:** $440.62K

**Visuals Included:**
- Revenue Trend Overtime (line chart, Jul 1996 – May 1998)
- Employees' Performance table (Total Revenue, AOV, Country, City)
- Revenue Total for New vs. Old Customers (stacked bar chart by month)

---

### 2. Shipment Analysis
Monitors delivery performance and overdue shipment trends across shippers and customers.

**Key Metrics:**
- **In-Time Shipments:** 688
- **Overdue Shipments:** 125
- **AVG Shipment Duration:** 8.51 days
- **% Overdue Shipments:** 15%

**Visuals Included:**
- AVG Shipment Duration Overtime (line chart with configurable time limit threshold)
- % Overdue Shipments by Year, Quarter, and Month
- Overdue Shipments by Year, Month, and Company Name (stacked bar by shipper)
- Customers' Statistics table (overdue shipment count per company)
- Shippers' Statistics table (AVG shipment duration and % overdue by carrier)

---

## Filters & Interactivity 🎛️

Both dashboards support dynamic filtering across:
- **Categories** — product category segmentation
- **Regions** — geographic filtering
- **Period** — quarterly or custom period selection
- **Date Range** — slider and date picker (Jul 1996 – May 1998)
- **Shipment Time Limit** — adjustable threshold (days) for overdue classification
- **Max % of Overdue Shipments** — configurable alert threshold

---

## Tools Used 🛠️

- **Power BI** — dashboard design and interactive visualizations
- **NorthWind Database** — source dataset (orders, shipments, employees, customers)

---

## Key Insights 🔍

- **Federal Shipping** is the best-performing carrier with the lowest AVG shipment duration (7.40 days) and lowest overdue rate (10%)
- **United Package** has the highest overdue rate at 19% with an average duration of 9.29 days
- Revenue shows a strong upward trend from late 1997 into early 1998, peaking around March 1998
- **Margaret Peacock** is the top-performing sales representative with $232,890 in total revenue
- New customer revenue contribution remains consistent but is outpaced by returning customers month over month

---

## Author ✍️

**Steven Nguyen** — Temple University
