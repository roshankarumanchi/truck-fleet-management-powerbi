# 🚛 Truck Fleet Management Dashboard — Power BI

An interactive Power BI dashboard built to analyse and monitor the operational performance of a truck fleet across Ireland. The dashboard provides actionable insights into delivery efficiency, driver performance, fuel consumption, maintenance costs, and customer satisfaction.

---

## 📊 Project Overview

This project simulates a real-world logistics and fleet management scenario with **5,000 delivery records** across 7 regions in Ireland. The goal was to build a comprehensive analytics solution that helps fleet managers make data-driven decisions to reduce delays, cut costs, and improve customer satisfaction.

---

## 🗺️ Dataset

**File:** `Truck_fleet_data.csv`  
**Records:** 5,000 deliveries  
**Coverage:** Ireland (Dublin, Cork, Galway, Limerick, Kildare, Meath, Waterford)

| Column | Description |
|--------|-------------|
| `Delivery_ID` | Unique delivery identifier |
| `Truck_ID` | Truck assigned to the delivery |
| `Vehicle_Type` | Refrigerated Truck, Articulated Truck, Van, Rigid Truck |
| `Truck_Age_Years` | Age of the vehicle |
| `Vehicle_Status` | Active / Maintenance |
| `Driver_ID / Driver_Name` | Driver assigned |
| `Driver_Experience_Years` | Years of experience |
| `Driver_Performance_Score` | Performance rating (0–100) |
| `Driver_Behaviour_Score` | Behaviour rating (0–100) |
| `Delivery_Date` | Date of delivery |
| `Route_Region` | Region of delivery |
| `Route_Distance_KM` | Distance covered (km) |
| `Delivery_Status` | On-Time / Delayed / Failed |
| `Delay_Hours` | Hours of delay (if any) |
| `Delay_Reason` | Traffic / Vehicle Breakdown / Driver Issue / Weather / Route Inefficiency |
| `Fuel_Consumed_Liters` | Fuel used per delivery |
| `Fuel_Cost_EUR` | Cost of fuel (€) |
| `Maintenance_Cost_EUR` | Maintenance cost (€) |
| `Breakdown_Count` | Number of breakdowns |
| `Downtime_Hours` | Total downtime hours |
| `Customer_Satisfaction_Score` | Rating (1–10) |
| `Complaint_Category` | Type of complaint raised |
| `Delivery_Revenue_EUR` | Revenue per delivery (€) |
| `Revenue_Loss_EUR` | Revenue lost due to delays/failures (€) |

---

## 📈 Dashboard Features

- **Fleet Overview** — Active vs. maintenance vehicles, vehicle type breakdown, truck age distribution
- **Delivery Performance** — On-time vs. delayed vs. failed delivery rates by region and vehicle type
- **Delay Analysis** — Root cause breakdown (traffic, breakdowns, driver issues, weather, route inefficiency)
- **Driver Performance** — Performance and behaviour scores, experience vs. delivery success correlation
- **Cost Analysis** — Fuel cost, maintenance cost, and revenue loss tracking across regions
- **Customer Satisfaction** — Complaint categories, satisfaction scores, and open complaint tracking
- **Regional Insights** — Route-level performance across Dublin, Cork, Galway, Limerick, Kildare, Meath, and Waterford

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development and data visualisation
- **DAX (Data Analysis Expressions)** — Custom KPIs and calculated measures
- **Power Query** — Data cleaning and transformation
- **CSV** — Raw data source

---

## 🚀 How to Open

1. Clone or download this repository
2. Open `Truck_fleet_management.pbix` in **Power BI Desktop**
3. If prompted, point the data source to `Truck_fleet_data.csv` in the same folder
4. Explore the dashboard across all pages

> **Note:** Power BI Desktop is free to download from [Microsoft](https://powerbi.microsoft.com/desktop/)

---

## 💡 Key Insights

- Identified the top delay reasons contributing to revenue loss across Irish regions
- Highlighted underperforming drivers based on behaviour and performance scores
- Tracked maintenance cost spikes correlated with older vehicle age
- Mapped regional delivery failure rates to support route optimisation decisions

---

## 👤 Author

**Roshan**  
MSc Data Analytics — National College of Ireland, Dublin  
[LinkedIn](https://www.linkedin.com/in/) | [GitHub](https://github.com/)
