# Flight-Data-Analysis
Analysed aviation datasets to derive trends in revenue and seat efficiency.

## 🔍 Overview
This project delivers insightful airline operations analysis using SQL. It explores flight schedules, aircraft usage, booking behaviours, and revenue metrics from a structured relational database. Each query addresses a real-world airline KPI and reflects data-driven thinking.

---

## 🧠 Problem Statement
Airlines generate extensive operational data across various systems. This project focuses on extracting insights across:
- ✈️ Flight punctuality and delays  
- 🛫 Aircraft utilisation and seat occupancy  
- 💰 Revenue performance by flight and route  
- 🧍‍♂️ Passenger behaviour and booking trends

---

## 📁 Dataset Summary
The database schema models real-world airline operations and includes:
- **Flights** – Schedules, aircraft, and airport routing  
- **Aircraft** – Models and seat layouts  
- **Airports** – Location metadata  
- **Bookings & Tickets** – Reservation-level financial data  
- **Ticket Flights & Boarding Passes** – Passenger-flight linkage and seating

---

## 🧹 Data Cleaning Highlights
- Handled missing values with `IS NOT NULL` filters  
- Used `COALESCE()` for null joins in seat occupancy  
- Converted timestamps to readable formats using `DATE()` and `DATE_FORMAT()`  
- Followed consistent aliasing and query formatting for readability

---

## 📊 Analysis Summary

A total of 17 analytical queries are designed to answer questions like:
- Which flights had the most delay?
- What is the revenue per flight and per route?
- Which aircraft are most and least utilised?
- What are the peak hours for bookings?
- How do fare types affect revenue distribution?

All queries are modular and extensible for BI platforms like Power BI or Tableau.

---

## 🚀 How to Use
1. Set up MySQL or any compatible SQL client  
2. Load the airline schema and sample data using provided SQL scripts  
3. Execute the analysis queries  
4. Optionally plug results into dashboards for visualisation

---

## 💡 Skills Demonstrated
- ✅ SQL proficiency: `JOIN`, `GROUP BY`, `CTEs`, `aggregations`, time functions  
- ✅ Real-world schema interpretation  
- ✅ Data cleaning and alias best practices  
- ✅ Domain insights into airline operations

---

## 🔖 GitHub Tags (Recommended)
`SQL` `Airline Analytics` `Data Analysis` `MySQL` `Booking Trends` `Flight Revenue` `Business Intelligence`
