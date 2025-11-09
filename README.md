# 🧠 Log-Analysis-Python-Tata_Steel_Internship

This repository contains the complete work, code, documentation, and reports from my **Data Analysis Internship at TATA Steel Ltd (SNTI Division)**.  
The project focuses on **Log File Analysis using Python** — turning large, unstructured system logs into meaningful, actionable insights through **data cleaning, processing, visualization, and database integration**.

---

## 🏢 Organization
**Company:** TATA Steel Ltd  
**Department:** SNTI (IT Division)  
**Mentor:** Mr. Anup Kumar  
**Intern:** Utkarsh Anand  
**Duration:** 22 July 2024 – 24 October 2024  
**Training Code:** VT20245542  

---

## 🎯 Project Overview

The goal of this internship project was to design and implement a complete **data analysis workflow** using Python — from raw **log data parsing** to **visualization and database integration** — while ensuring performance, scalability, and data integrity.

This project served as a bridge between academic learning and real-world application, reinforcing core concepts in **Python programming**, **data analysis**, and **database management**.

---

## 🧩 Objectives

1. **Analyze Log Files** — Extract useful information from large, unstructured log files.  
2. **Data Cleaning** — Handle duplicates, missing values, and format inconsistencies.  
3. **Insight Extraction** — Identify error frequencies, usage patterns, and user activity trends.  
4. **Data Visualization** — Create graphs and dashboards for better interpretation.  
5. **Automation** — Process multiple log files simultaneously with scalability.  
6. **Database Integration** — Store processed data in a **SQLite** database for querying.  
7. *(Optional)* Develop a lightweight web interface for displaying processed results.

---

## ⚙️ Methodology

### 1️⃣ Log File Analysis
- Parsed both **plain text** and **JSON** logs.  
- Extracted key details: timestamps, log levels (INFO, ERROR, WARNING), user IDs, and event messages.  
- Used **Regular Expressions (`re` module)** for text-based parsing.  
- Used **`json` module** for structured data extraction.

### 2️⃣ Data Cleaning
- Removed duplicates and handled missing/corrupted entries.  
- Standardized date/time formats and data types.  
- Ensured privacy by anonymizing sensitive user data.

### 3️⃣ Data Processing & Insights
- Employed **pandas DataFrames** for data aggregation and statistical computation.  
- Extracted metrics like:
  - Error frequencies  
  - Peak usage hours  
  - User activity distributions  
  - System performance summaries

### 4️⃣ Visualization
Used Python libraries to visualize patterns:
- **Matplotlib:** For line plots, bar charts, and histograms  
- **Seaborn:** For advanced, aesthetic visualizations (heatmaps, pairplots, etc.)

**Sample Visualizations:**
- Error frequency bar chart  
- Daily usage line plot  
- User activity heatmap  
- Device distribution pie chart  

### 5️⃣ Handling Multiple Files
- Automated multi-file log ingestion using **`os`** and **`glob`**.  
- Implemented **multiprocessing** for faster data processing across large datasets.

### 6️⃣ Database Integration
- Used **SQLite** for structured storage and querying.  
- Tables designed for:
  - Errors and frequency tracking  
  - User activity and timestamps  
  - System usage metrics  
- Added indices for faster performance.  

---

## 🧰 Tools & Technologies

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3.x |
| **IDE / Notebook** | Jupyter Notebook |
| **Data Handling** | pandas, numpy |
| **Data Parsing** | re, json, os, glob |
| **Visualization** | matplotlib, seaborn |
| **Database** | SQLite |
| **Version Control** | Git |
| **Environment** | venv (virtual environments) |

---

## 🚀 Implementation Structure
