# 🚕 Uber Trip Analysis Dashboard (Power BI)

This project presents an end-to-end interactive dashboard built in **Power BI** to analyze Uber trip data. The dashboard offers a comprehensive view of booking trends, revenue generation, trip distances, vehicle types, and time-based patterns, empowering stakeholders to make informed decisions.

All data transformations were done directly in **Power BI using Power Query Editor**, with the raw dataset provided in Excel format (`.xlsx`).

---

## 🎯 Business Objective

To uncover key patterns in Uber trip data that help:

- Monitor booking volume, revenue, and trip efficiency
- Identify demand fluctuations across time and locations
- Optimize pricing, resource planning, and vehicle allocation
- Provide stakeholders with actionable visual insights

---

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **Power Query Editor** (for data cleaning and transformation)
- **DAX** (for KPIs and dynamic measures)
- **Excel** (`.xlsx` as the data source)

---

## 📊 Dashboards & Key Features

### 📍 **Dashboard 1: Overview Analysis**
- **KPIs**:
  - Total Bookings
  - Total Booking Value
  - Average Booking Value
  - Total Trip Distance
  - Average Trip Distance
  - Average Trip Time
- **Visuals**:
  - Bar/line charts for trip trends
  - Slicers for Date, City, and Category
  - Matrix grid for Vehicle Type comparison
- **Add-ons**:
  - Dynamic measure selector via disconnected table
  - Conditional formatting on metrics
  - Clear slicers button
  - Download raw data button (Power Automate support)
  - Dynamic chart titles
  - Tooltips for deeper insight

---

### ⏱️ **Dashboard 2: Time-Based Analysis**
- **Global Dynamic Measure** that updates all visuals:
  - Total Bookings
  - Total Booking Value
  - Total Trip Distance
- **Visuals**:
  - Area chart by pickup time (10-minute intervals)
  - Line chart by weekday
  - Heatmap (Hour vs. Day) to detect peak hours
- Helps in understanding hourly and daily demand cycles

---

### 🔍 **Dashboard 3: Details Tab**
- **Grid Table View** showing trip-level details
- **Drill-through Functionality** from all visuals
- **Bookmarks**:
  - Toggle between filtered view and full dataset
- Useful for granular inspection of individual trip records

---

## 🌍 Location-Based Insights

- **Most Frequent Pickup & Drop-off Points**
- **Farthest Trip** by distance
- **Top 5 Booking Locations**
- **Most Preferred Vehicle per Location**

These insights assist in improving dynamic pricing, forecasting demand, and strategic vehicle positioning.

---

## 📁 Folder Structure
- Data : https://github.com/priyash-ux/Uber-Trip-Analysis-dashboard/blob/main/Uber%20Trip%20Details.xlsx <br/>
- Dashboard : https://github.com/priyash-ux/Uber-Trip-Analysis-dashboard/blob/main/uber.pbix <br/>
- Dashboard snapshots : ![Dashboard_1(overview_analysis)](https://github.com/user-attachments/assets/794ebbd0-26b8-463b-82fa-017c6b90bddf) <br/>
                        ![Dashboard_2(Time_Analysis)](https://github.com/user-attachments/assets/f56db28e-5c04-4393-9a4f-0c2e4bf73991)


   

