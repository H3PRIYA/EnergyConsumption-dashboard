# ⚡ Energy Consumption Dashboard

An interactive Power BI dashboard for tracking and analyzing **Water, Electricity, and Gas** consumption and costs across multiple cities and buildings.

## 📊 Overview

This dashboard provides a consolidated view of energy consumption data (Water, Electricity, Gas) from **2016 to 2019**, enabling users to monitor total cost, units consumed, and trends by city, building, and date.

The report contains **4 pages**:

| Page | Description |
|------|--------------|
| **Overview** | Summary landing page with navigation to Water, Electricity, and Gas sections |
| **Water** | Total cost and consumption trends, monthly breakdown table, and cost by city |
| **Electricity** | Total cost and consumption trends, monthly breakdown table, and cost by city |
| **Gas** | Total cost and consumption trends, monthly breakdown table, and cost by city |

## ✨ Features

- **KPI Cards** – Total Cost and Units Consumed at a glance
- **Interactive Slicers** – Filter by City, Building, and Date range
- **Trend Analysis** – Line chart of Total Cost by Date and Consumption Type
- **City-wise Breakdown** – Donut chart showing % share of Total Cost by City (New York, Chicago, Los Angeles, Phoenix, Houston)
- **Detailed Table** – Year, Quarter, Month, Unit Consumed, and Total Cost
- **Drillthrough & Cross-report Filtering** – Seamless navigation between report pages
- **Consistent Theming** – Dark blue and orange color palette for readability

## 🗂️ Data Model

The report is built on the following tables:

- **Building Master** – Building and city reference data
- **Energy Consumptions** – Fact table with date, consumption type, units consumed, and cost
- **Rates** – Rate/pricing reference data used for cost calculations

## 🛠️ Tech Stack

- **Tool:** Microsoft Power BI Desktop
- **Data Modeling:** Power Query (M) + DAX measures
- **Visuals:** Native Power BI visuals (line chart, donut chart, table, cards, slicers)

## 📸 Screenshots

<img width="1264" height="745" alt="image" src="https://github.com/user-attachments/assets/900bc822-ea87-4d13-9c56-a6b35c8db0fc" />

<img width="1259" height="740" alt="image" src="https://github.com/user-attachments/assets/908e43da-4d8b-4767-bd6c-0c0525d1260a" />
<img width="1275" height="742" alt="image" src="https://github.com/user-attachments/assets/75a707b5-1717-48e5-8274-3a158580d7f5" />
<img width="1230" height="739" alt="image" src="https://github.com/user-attachments/assets/671ba899-cdbf-43c5-9410-73bab963d494" />

📌 Notes
Date range covered: Jan 2016 – Dec 2019
Cities included: New York, Chicago, Los Angeles, Phoenix, Houston
Filters (City, Building, Date) apply across all consumption-type pages

