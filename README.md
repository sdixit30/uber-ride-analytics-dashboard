# 🚗 Uber Ride Analytics Dashboard | Power BI

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-000000?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/dax/)
[![Power Query](https://img.shields.io/badge/Power_Query-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://learn.microsoft.com/en-us/power-query/)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

An interactive Power BI dashboard analyzing Uber ride bookings, revenue trends, payment method distribution, rider behavior, and peak demand patterns — built to turn raw ride-booking data into actionable business insights.

---

## 📌 Project Overview

This project analyzes end-to-end ride-booking operations for a ride-hailing service across **6 interactive report pages**, covering completed/cancelled bookings, vehicle-wise performance, revenue by payment method, rider segmentation, and time/location-based demand patterns — the kind of report an operations or growth team would use to make data-driven decisions.

**Tools used:** Power BI Desktop · DAX · Power Query · Excel

**Scale analyzed:** ~104K bookings · ₹5.18M+ revenue · 6 vehicle types (Auto, Bike, Go Mini, Go Sedan, Premier Sedan, Uber XL)

---

## 🧩 Dashboard Pages & Insights

### 1. Overview
93K completed bookings, 57K lost, ₹52M total revenue. Auto leads vehicle revenue at ₹13M, followed by Bike (₹11M) and Go Mini (₹10M). Total distance: 2.51M, avg 24.64/ride. Top pickup: Khandsa (600); top drop: Ashram (592). Customer rating: 4.40/5, Driver rating: 4.23/5.

### 2. Vehicle Performance
Detailed breakdown by vehicle type. Auto generated ₹1.28Cr revenue from 32,948 customers — the highest-earning vehicle. Bike leads in booking volume (33,010 bookings), while Premier Sedan and Uber XL earn more per ride despite lower volume — a clear volume-vs-margin trade-off across the fleet.

### 3. Sparkline
A compact, at-a-glance view combining every vehicle's revenue, bookings, and monthly trend in one table. 23,128 completed bookings recorded for Auto alone, contributing 100% share in this filtered view. Monthly patterns show steady demand with a mid-year dip and later recovery.

### 4. Revenue Analysis
₹52M total revenue, peaking in select months (4.42M–4.67M range). UPI dominates payments at ₹23M, nearly double Cash (₹13M), followed by Uber Wallet, Credit Card, and Debit Card. Revenue is spread across top customers, led by C7828101 at 7.7K.

### 5. Rider Insights
Customer-level detail with cancellation reasons and payment behavior. Top cancellation reason: "AC is not working" (1,155 bookings). UPI remains the preferred payment method (37K customers), followed by Cash (16K) and Uber Wallet (11K). Average distance per ride: 24.64.

### 6. Location & Demand
Peak demand: 6–9 PM with 5,095 rides, the busiest window by far. Slowest period: 12–3 AM (594 rides). Badarpur and Kanhaiya Nagar lead as top-distance zones (163 each). Riders segmented into 18K first-time, 2,505 returning, and 8 regular customers — useful for retention strategy.

---

## 🎯 Key Business Insights

- **Auto is the backbone** of both ride volume and revenue across the fleet
- **UPI is the dominant payment method** across every view — strong digital adoption among riders
- **6–9 PM is peak demand** — a clear signal for driver allocation and surge planning
- **Badarpur and Kanhaiya Nagar** are high-traffic zones worth prioritizing for driver availability
- **Vehicle mix reveals a trade-off**: Bike/Auto drive volume, Premier Sedan/Uber XL drive margin
- Customer and driver satisfaction remain strong (4.40/5 and 4.23/5 respectively)
- **"AC not working"** is a top cancellation driver — a clear, fixable operations issue

---

## 🛠️ Skills Demonstrated

- Business requirement gathering & KPI definition
- Data modeling and DAX measures (dynamic KPIs, month/quarter toggles)
- Power Query data cleaning and transformation
- Multi-page interactive report design with filters, slicers, and drill-throughs
- Insight storytelling for stakeholder-ready reporting

---

## 📂 Files in this Repo

| File | Description |
|---|---|
| `Uber_Dashboard.pbix` | Full working Power BI file — download and open in Power BI Desktop to explore live |
| `Uber_Dataset.xlsx` | Raw dataset used to build the dashboard |

