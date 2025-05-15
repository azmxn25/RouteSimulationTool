# 🚚 Route Efficiency Simulation Tool

A lightweight Python tool for simulating vehicle telematics trip data and analyzing route efficiency. This project evaluates average fuel consumption, distance traveled, and driving speed, exporting the results to a CSV file suitable for visualization in Power BI or Excel.

---

## 📌 Overview

This tool generates synthetic trip records for a small vehicle fleet and calculates route-level performance metrics. It's useful for prototyping telematics analysis, modeling fleet behavior, or academic projects involving mobility data.

---

## 🧠 Features

- Simulates trips for multiple vehicles across different routes
- Stores data in a local SQLite database (`telematics.db`)
- Calculates route-level metrics:
  - Average distance per trip
  - Average fuel used
  - Fuel efficiency (km/L)
  - Average speed (km/h)
- Outputs results to `route_efficiency_report.csv` for dashboarding

---

## 📂 Sample Output (CSV)

| Route ID | Total Trips | Avg Distance (km) | Avg Fuel Used (L) | Avg Fuel Efficiency (km/L) | Avg Speed (km/h) |
|----------|--------------|-------------------|--------------------|-----------------------------|------------------|
| R1       | 50           | 68.2              | 7.2                | 9.47                        | 61.3             |
| R2       | 52           | 71.6              | 7.5                | 9.55                        | 62.0             |
| R3       | 48           | 66.9              | 6.9                | 9.69                        | 60.1             |

---

## 🚀 Getting Started

### 🔧 Requirements

- Python 3.6 or higher
- No external dependencies required

### ▶️ How to Run

copy the code and run on your python 
