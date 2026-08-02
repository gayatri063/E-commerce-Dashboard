# Transportation & Logistics Analytics Dashboard

This repository contains an end-to-end Microsoft Power BI Business Intelligence project focused on logistics and transportation analytics. The project demonstrates data modeling, KPI development, interactive dashboard design, and operational performance analysis using a relational logistics dataset.

---

## Repository Structure

| File Name | File Type | Records / Size | Project Description |
| :--- | :--- | :--- | :--- |
| **Transportation_And_Logistics_Dashboard.pbix** | Power BI Report (.pbix) | ~1 MB | Interactive dashboard for shipment operations, warehouse performance, revenue, and logistics analytics. |
| **Logistics_Transportation_Dataset.xlsx** | Excel Dataset (.xlsx) | 25,000 Rows | Relational logistics dataset containing shipment transactions, customers, drivers, vehicles, warehouses, and routes. |

---

## Project Definition & Business Objective

The **Transportation & Logistics Dashboard** is an executive business intelligence solution designed to monitor logistics operations, shipment performance, warehouse efficiency, and financial performance. Built using a relational dataset of 25,000 shipment records, the dashboard provides insights into revenue generation, operational costs, shipment distribution, and warehouse productivity, helping logistics managers make data-driven decisions.

```
+------------------------------------------------------------------------------------------------------+
|                    TRANSPORTATION & LOGISTICS DASHBOARD                                              |
+------------------------------------------------------------------------------------------------------+
| [ Total Revenue ] [ Total Cost ] [ Total Profit ] [ Total Shipments ] [ Delivered ] [ Success Rate ] |
+-------------------------------------------+----------------------------------------------------------+
| Global Shipment Distribution              | Shipment Status Distribution                            |
| (Filled Map)                              | (Donut Chart)                                           |
+-------------------------------------------+----------------------------------------------------------+
| Top Shipment Cities                       | Shipments by Warehouse                                  |
| (Treemap)                                 | (Stacked Column Chart)                                  |
+-------------------------------------------+----------------------------------------------------------+
| Profit by Vehicle Type                    | Revenue by Vehicle Type                                 |
| (Waterfall Chart)                         | (Donut Chart)                                           |
+-------------------------------------------+----------------------------------------------------------+
| Shipment Status Trend by Warehouse        | Warehouse Performance Summary                           |
| (Ribbon Chart)                            | (Interactive Matrix)                                    |
+------------------------------------------------------------------------------------------------------+
```

---

## Core Key Performance Indicators (KPIs)

* **Total Revenue** – Total revenue generated from all completed shipments.
* **Total Cost** – Overall operational costs, including transportation expenses.
* **Total Profit** – Net profit calculated as Revenue minus Total Cost.
* **Total Shipments** – Total number of shipment transactions processed.
* **Delivered Shipments** – Count of successfully delivered shipments.
* **Delivery Success Rate** – Percentage of shipments delivered successfully.

---

## Dashboard Visualizations & Analytics

1. **Global Shipment Distribution**  
   Interactive Filled Map displaying shipment density across origin cities.

2. **Shipment Status Distribution**  
   Donut Chart showing the proportion of Delivered, Delayed, In Transit, and Cancelled shipments.

3. **Top Shipment Cities**  
   Treemap highlighting cities contributing the highest shipment volume.

4. **Shipments by Warehouse**  
   Stacked Column Chart comparing shipment volumes across warehouses.

5. **Profit by Vehicle Type**  
   Waterfall Chart illustrating profit contribution by different vehicle types.

6. **Revenue by Vehicle Type**  
   Donut Chart displaying revenue distribution across trucks, vans, and trailers.

7. **Shipment Status Trend by Warehouse**  
   Ribbon Chart visualizing how shipment status varies across warehouses.

8. **Warehouse Performance Summary**  
   Interactive Matrix Table summarizing shipment count, revenue, and profit for each warehouse.

---

## Source Data Dictionary (`Logistics_Transportation_Dataset.xlsx`)

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| **ShipmentID** | Identifier | Unique shipment reference number. |
| **CustomerID** | Identifier | Unique customer identifier. |
| **DriverID** | Identifier | Assigned driver for each shipment. |
| **VehicleID** | Identifier | Vehicle used for transportation. |
| **WarehouseID** | Identifier | Origin warehouse handling the shipment. |
| **RouteID** | Identifier | Assigned transportation route. |
| **BookingDate** | Temporal | Date the shipment was booked. |
| **DistanceKM** | Numeric | Distance travelled in kilometers. |
| **Revenue** | Numeric (Currency) | Revenue earned from the shipment. |
| **TotalCost** | Numeric (Currency) | Total transportation and operational cost. |
| **Profit** | Numeric (Currency) | Net profit generated from the shipment. |
| **Status** | Categorical | Shipment status (*Delivered, In Transit, Delayed, Cancelled*). |

---

## Interactive Features

The dashboard supports interactive filtering through slicers, including:
* Booking Date
* Shipment Status
* Warehouse ID
* Vehicle ID
* Driver ID
* Customer ID

All visuals are interconnected through cross-filtering and drill-down capabilities for deeper operational analysis.

---

## Business Insights

The dashboard enables logistics managers to:
* Monitor shipment performance across warehouses.
* Track operational revenue, costs, and profitability.
* Analyze shipment distribution geographically.
* Compare warehouse productivity.
* Identify shipment status trends.
* Evaluate vehicle contribution to business performance.
* Improve operational efficiency through data-driven decision-making.

---

## Dashboard Preview

![Dashboard Preview](Dashboard.png)

---

## Repository Structure

```
Transportation-Logistics-Dashboard/
│
├── Transportation_And_Logistics_Dashboard.pbix
├── Logistics_Transportation_Dataset.xlsx
├── Dashboard.png
└── README.md
```

---

## Skills Demonstrated

* Microsoft Power BI
* Power Query (ETL)
* Data Modeling (Star Schema)
* DAX Measures & Calculated Columns
* KPI Development
* Interactive Dashboard Design
* Business Intelligence Reporting
* Data Visualization
* Logistics & Supply Chain Analytics
* Analytical Storytelling

---

## Getting Started

### Prerequisites

Install Microsoft Power BI Desktop on Windows.

### Opening the Dashboard

1. Open `Transportation_And_Logistics_Dashboard.pbix` in Power BI Desktop.
2. Explore the dashboard using slicers, drill-down, and cross-filter interactions.
3. Analyze shipment operations, warehouse performance, and financial KPIs.

### Data Source Updates

If refreshing the report, update the data source path to `Logistics_Transportation_Dataset.xlsx` located in this repository.

---

## Author

**Gayatri Jawalkar**  
*Data Analyst | Power BI | SQL | Excel | Python*

Passionate about building interactive dashboards that transform raw operational data into actionable business insights.
