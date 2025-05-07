# 🚕 Rapido Trip Analytics – Bangalore Region (Power BI Dashboard Project)

## 📊 Project Overview

This Power BI project presents a comprehensive data analysis of **Rapido's trip data in the Bangalore region**, aimed at providing stakeholders with actionable insights on trip efficiency, booking trends, revenue performance, and location-based analysis. The dashboards are designed to support **strategic decision-making**, **resource optimization**, and **customer experience improvement** through clear and interactive data visualizations.

---

## 🎯 Business Requirement

The objective of this project was to:
- Analyze trip patterns and revenue generation.
- Visualize trip activity based on time, location, and vehicle.
- Enable dynamic filtering and drill-through for granular data exploration.
- Empower business stakeholders to optimize pricing models, fleet deployment, and rider satisfaction.

---

## 💡 Key Features & KPIs

### Dashboard 1: **Trip Overview**
- **Total Bookings** – Count of trips taken.
- **Total Booking Value** – Revenue from completed trips.
- **Average Booking Value** – Revenue per trip.
- **Total Trip Distance** – Sum of all distances covered.
- **Average Trip Distance** – Mean distance per ride.
- **Average Trip Time** – Mean duration per ride.

### Visual Components:
- Dynamic Measure Selector (Disconnected Table approach)
- Booking Analysis by:
  - Payment Type (Cash, Card, Wallet, etc.)
  - Trip Type (Day/Night)
- **Vehicle-wise KPI Matrix** with conditional formatting
- **Total Bookings by Day** – Line Chart

---

### Dashboard 2: **Time Analysis**
- **Pickup Time Intervals** – 10-min grouping (Area Chart)
- **Weekday Trend** – Line Chart (Mon to Sun)
- **Hourly Heatmap** – Matrix grid of bookings by hour and weekday

🔄 **Global Dynamic Measure** affecting all visuals:
- Total Bookings  
- Total Booking Value  
- Total Trip Distance  

---

### Dashboard 3: **Detailed Drill-Through View**
- Detailed grid with trip-level data:
  - Trip ID, Time, Distance, Pickup & Drop Locations
- Drill-through support from all visuals
- **Bookmarks** for:
  - Filtered drill-through view
  - Full dataset view

---

## 🧠 Advanced Enhancements

- **USERELATIONSHIP()** DAX function to activate inactive relationships for Drop-off Location context
- **Dynamic Titles** based on selected measure
- **Clear Slicers Button** for resetting all filters
- **Raw Data Export Button** via Power Automate or native export
- Tooltips showing average and supporting metrics
- **Location-based Preferred Vehicle Analysis**

---

## 🗂️ Data Model

### Tables Used:
- **Trips**
  - Trip ID, Pickup/Dropoff Time, Fare, Surge Fee, Distance, Passenger Count, Payment Type, etc.
- **Locations**
  - Location ID, Location Name, City
- **Date Table** (custom)
  - Used for all time-based slicers and relationships

> Special care was taken to manage **inactive relationships** between DOLocationID and the Locations table, enabling location insights with `USERELATIONSHIP()` in DAX.

---

## 🧪 Tools & Technologies

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **Power Query** (M Language for ETL)
- **Excel / CSV** as data source
- **Power Automate** for export enhancement
- **GitHub** for version control and collaboration

---

## 🧭 Outcomes

✔ Identified booking hotspots & underutilized time slots  
✔ Provided operational intelligence for vehicle allocation  
✔ Revealed behavioral patterns across time, day, and location  
✔ Delivered a user-friendly and highly interactive BI experience  

---

## 📸 Screenshots




