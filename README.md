# Metro Construction Health Monitor Dashboard

## 📌 Project Overview

This project is a web-based dashboard built to analyze and monitor the health of a construction project using RFI (Request for Inspection) data.

The dashboard transforms raw CSV data into actionable insights by visualizing project performance, identifying delays, and highlighting quality issues.

---

## 🎯 Objective

To build an interactive dashboard that:

* Tracks RFI closure progress
* Identifies SLA breaches
* Analyzes approval vs rejection trends
* Detects potential quality and performance issues

---

## 📂 Dataset

The application uses a CSV dataset containing 500 RFIs with fields such as:

* rfi_id
* package
* station
* subsystem_type
* raised_date
* sla_deadline
* closed_date
* result

---

## ⚙️ Features

### ✅ Data Ingestion

* Upload CSV file dynamically
* Parses data using JavaScript

### 📊 Dashboard Visualizations

* RFI Closure Rate by Package
* SLA Breach Count by Station
* Approval vs Rejection Trend (Monthly)
* Additional custom chart

### 📋 Filterable Table

* Filter by:

  * Package
  * Station
  * Result
  * Date range

### 🚨 Rule Engine & Alerts

The system automatically detects issues and generates alert cards:

* 🔴 CRITICAL: RFIs open beyond SLA
* 🟠 WARNING: High rejection patterns
* 🟡 INFO: Additional insights

Each alert includes:

* Severity level
* Description
* Affected RFI IDs
* Recommended action

---

## 🧠 Key Logic Implemented

* SLA breach detection using date comparison
* Identification of open RFIs (missing closed_date)
* Rejection rate analysis for quality monitoring
* Data-driven rule-based alert system

---

## 🖥️ Tech Stack

* HTML
* CSS
* JavaScript
* Chart.js (for charts)
* PapaParse (for CSV parsing)

---

## ▶️ How to Run

1. Download or clone the project
2. Open the `index.html` file in any browser (Chrome recommended)
3. Upload the provided CSV dataset
4. Explore the dashboard and insights

---

## 🎥 Demo

A demo video is included (`demo.mp4`) showcasing:

* Dashboard functionality
* CSV upload
* Data visualization
* Alert generation

---

## 💡 Highlights

* Fully client-side application (no backend required)
* Works by simply opening the HTML file
* Interactive and user-friendly interface
* Designed for real-world project monitoring use

---

## 🚀 Future Improvements

* Predict SLA breaches using historical data
* Text analysis on remarks field
* Export reports as PDF
* Advanced filtering and search

---

## 👤 Author

Developed as part of AI-PMS Selection Hackathon.

---

## 📌 Note

This project demonstrates how data analytics and visualization can improve decision-making in construction project management.
