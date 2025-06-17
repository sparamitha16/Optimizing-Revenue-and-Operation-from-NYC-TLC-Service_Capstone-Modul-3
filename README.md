
# Optimizing Revenue and Efficiency: A Data-Driven Analysis of NYC Taxi Operations

## Project Overview
This capstone project analyzes NYC Taxi operations to uncover actionable insights that enhance **revenue generation** and **operational efficiency** amidst growing competition from ride-hailing services.

---

## Problem Statement
**How can the NYC Taxi & Limousine Commission increase profitability while improving the operational efficiency of its taxi fleet?**

---

## Business Objectives

### A. Revenue Optimization
- Identify high-revenue pickup zones and time slots.
- Calculate revenue per mile and per minute.
- Understand patterns in day-of-week and hour-of-day revenue generation.

### B. Operational Efficiency
- Analyze trip speed and duration to detect inefficiencies.
- Spot underutilized zones or time windows.
- Measure idle time and its effect on trip volume.

---

## Dataset

- **Source:** NYC Taxi and Limousine Commission (TLC)
- **Dataset:** Yellow Taxi Trip Data
- **Period Covered:** January 2023
- **Size:** Millions of records on trips, timestamps, distances, fare components, and location IDs

---

## Tools & Technologies

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn
- **Visualization:** Looker Studio
- **Other Tools:** Google Colab, NYC TLC Data Dictionary

---

## Methodology

1. **Data Cleaning & Preprocessing**
   - Handling missing values, filtering outliers (e.g., extreme trip durations or distances), and converting time columns.

2. **Key Metrics Calculated**
   - Revenue per trip, per mile, per minute
   - Tip rate
   - Idle time between trips
   - Speed and trip efficiency

3. **Exploratory Data Analysis**
   - Revenue distribution, heatmaps of tips and revenue by time and borough, trip trends by hour, etc

---

## Key Insights

- **Peak revenue** occurs on **weekend evenings**, with **downtown Manhattan** being a consistent top-performing pickup zone.
- **Tips and fare amounts** spike during late-night and early-morning hours, particularly on **Fridays and Saturdays**.
- Several zones experience **high idle time** and **low-speed trips**, suggesting potential inefficiencies.
- There are **time slots with high trip volume but low revenue per minute**, indicating poor utilization.

---

## Strategic Recommendations

- **Prioritize driver deployment** 
in East Harlem (weekdays) and Bronx (efficient long trips).
- **Incentivize early morning shifts**
(3–6 AM) and weekend service with targeted bonuses.
- **Reward drivers in tip-friendly zones**
like Brooklyn; encourage great service on short trips.
- **Investigate underused zones** 
(e.g., WTC, Sutton Place); assess demand or access issues.
- **Enhance driver tools** 
with real-time “hot zone” alerts and hourly trip insights.
- **Customize strategies by day:** 
Weekday = commuters, Weekend = long/leisure rides.

