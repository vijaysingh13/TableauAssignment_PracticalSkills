# Urban Mobility & Public Transport Performance Dashboard
A comprehensive Tableau analytics solution designed for city managers, transport planners, and public service administrators to evaluate passenger demand, operational bottlenecks, and sustainability metrics across a municipal transit network.
---

## 📌 Project Overview
This project analyzes the **Metrovia Urban Mobility Dataset** (6,000 synthetic observations) to transform raw transit data into structured, actionable business intelligence. Organized into a 3-part Tableau Story narrative, the dashboards guide stakeholders through a logical decision-making sequence: from initial **Demand & Usage**, to **Service Performance**, and finally to **Sustainability & Mode Decisions**.

---

## 📊 Dashboard Architecture & Analytics

### 🔹 Dashboard 1: Urban Mobility Overview

Focuses on network-wide demand distribution across routes, time periods, and modes.
* **KPIs**: Total Passengers (overall network demand), Average Daily Passengers (typical usage baseline), and Number of Routes (network coverage context).
* **Monthly Passenger Demand Trend** *(Line Chart)*: Tracks demand fluctuations throughout the year to isolate recurring peak travel seasons from low-demand maintenance windows.
* **Passenger Demand by Route** *(Horizontal Bar Chart)*: Ranks busiest to least-used routes to prioritize vehicle capacity and scheduling resources.
* **Passenger Share by Transport Mode** *(Pie Chart)*: Illustrates modal share distribution across the transit ecosystem.

---

### 🔹 Dashboard 2: Delay and Service Performance

Diagnoses operational bottlenecks, service reliability, and timetable punctuality.

* **KPIs**: Average Delay (punctuality duration in minutes), On-Time Rate (percentage of trips delayed $\le 5$ minutes), and Service Completion Rate (percentage of non-cancelled scheduled trips).
* **Delay Heat Map** *(Heat Map)*: Cross-examines average delay by hour of day and day of week to highlight peak congestion windows.
* **Service Frequency vs. Delay** *(Scatter Plot)*: Identifies high-risk routes combining long headways, high passenger demand, and persistent delays.
* **Average Delay by Route** *(Horizontal Bar Chart)*: Pinpoints underperforming routes for root-cause infrastructure or timetable adjustments.

---

### 🔹 Dashboard 3: Sustainability and Mode Comparison

Evaluates transport modes by balancing service performance with environmental impact.

* **Transport Mode Performance Comparison** *(Highlight Table)*: Multi-metric view assessing average delay, occupancy, reliability, and satisfaction scales.
* **CO_2 Reduction & Modal Share** *(Dual-Axis Chart)*: Connects estimated environmental benefits with overall passenger adoption rates.
* **Passenger Demand vs. CO_2 Reduction** *(Scatter Plot)*: Isolates modes that maximize both high passenger volume and significant emission reductions.

---

## 💡 Strategic Recommendations

1. **Capacity Allocation**: Increase service frequency on top-ranked demand routes during high-intensity temporal windows identified in the Delay Heat Map.
2. **Targeted Interventions**: Prioritize operational audits on routes exhibiting high average delay, low completion rates, and low frequency.
3. **Sustainable Investment**: Balance funding decisions by cross-referencing modal demand with estimated $\text{CO}_2$ reduction metrics rather than relying solely on volume.

---

## 🛠️ Data & Tools Used

* **Business Intelligence**: Tableau Desktop / Tableau Public
* **Dataset**: Synthetic Metrovia Urban Mobility Dataset (6,000 rows)
* **Analytical Techniques**: Modal split analysis, trend forecasting, heat map grid profiling, dual-axis metric scaling
