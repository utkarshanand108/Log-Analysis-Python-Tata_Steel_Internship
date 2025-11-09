# 🧠 Data Analysis Projects — Utkarsh Anand

This repository contains two major data analysis projects that demonstrate end-to-end data analytics using Python — including data cleaning, exploratory data analysis (EDA), visualization, and insight generation.

---

## 📊 Project 1: Diwali Sales Data Analysis

### 📝 Overview
An Exploratory Data Analysis (EDA) project on **Diwali Sales Data**, aimed at identifying customer demographics, purchasing behavior, and sales trends using Python.

### 📂 Dataset
**File:** `Diwali Sales Data.csv`  
**Size:** 11,251 rows × 15 columns  
**Source:** Simulated retail sales data for Diwali season

### 🧰 Technologies Used
- **Python 3.x**
- **Pandas** — Data cleaning & manipulation  
- **NumPy** — Numerical computations  
- **Matplotlib / Seaborn** — Data visualization  
- **Jupyter Notebook** — Code execution and reporting  

### ⚙️ Key Steps
1. **Data Cleaning**
   - Removed irrelevant columns (`Status`, `unnamed1`)
   - Dropped null values and converted `Amount` column to integer type  
2. **EDA**
   - Gender-based spending analysis  
   - Age group and state-level purchase behavior  
   - Marital status and occupation trends  
   - Product category analysis  
3. **Visualization**
   - Count plots and bar plots using Seaborn  
   - Insights on gender, age, occupation, and product category

### 📈 Major Insights
- **Women (26–35 years)** dominate purchasing activity.  
- **Top States:** Uttar Pradesh, Maharashtra, Karnataka  
- **Top Occupations:** IT, Healthcare, Aviation  
- **Top Categories:** Food, Clothing, Electronics  

### 💡 Conclusion
> Married women aged **26–35 years**, working in **IT, Healthcare, or Aviation** and living in **Uttar Pradesh, Maharashtra, or Karnataka**, are the most likely to purchase items in **Food, Clothing, and Electronics** categories.

---

## 🧪 Project 2: TATA Steel Internship — Data Analysis Using Python

### 🏢 Organization
**Company:** TATA Steel Ltd  
**Department:** IT, SNTI Division  
**Mentor:** Mr. Anup Kumar  
**Duration:** 22 July 2024 – 24 October 2024  

### 🎯 Objective
To perform real-world data analysis on system and log files to extract insights on performance, user behavior, and trends — leveraging Python and SQLite.

### 🧩 Methodology
1. **Log File Analysis**
   - Parsed and interpreted large log datasets (plain text & JSON)
   - Extracted timestamps, log levels, user IDs, and events  

2. **Data Cleaning**
   - Removed duplicates, fixed missing values, standardized formats  

3. **Insight Extraction**
   - Computed error frequencies, user activity patterns, and peak usage times  

4. **Visualization**
   - Created bar charts, line plots, heatmaps, and pie charts using Matplotlib and Seaborn  

5. **Database Integration**
   - Stored processed results in SQLite database for querying  

6. **Automation**
   - Developed scripts for handling multiple log files concurrently using `os`, `glob`, and multiprocessing

### 🧰 Tools & Technologies
- **Python (pandas, re, json, matplotlib, seaborn, sqlite3)**  
- **Jupyter Notebook**
- **SQLite Database**
- **Git & Virtual Environments (venv)** for code versioning and dependency isolation  

### 🧠 Challenges & Solutions
| Challenge | Solution |
|------------|-----------|
| Unstructured log formats | Used regex & conditional parsing |
| Missing/corrupted data | Applied validation and replacement logic |
| Slow performance | Used multiprocessing & optimized data structures |
| Database insertion lag | Implemented bulk insert transactions |

### 📊 Results
Generated:
- Error frequency visualizations  
- System usage line graphs  
- User activity heatmaps  
- SQLite database tables for structured insights  

📁 **Project Drive Links:**  
[Bar Charts](https://drive.google.com/drive/folders/1yxlz2Jyd-oyBr8GVi6kvn4_oTbSr6_pa?usp=sharing)  
[Line Graphs](https://drive.google.com/drive/folders/1Ml6Zl8mzKqxdKYILLbsmwS13GnZHwX5Y?usp=sharing)  
[Code + Visualizations](https://drive.google.com/drive/folders/1kL4UFtK3bLv0DpVMHlXkuw_eSnsywaLY?usp=sharing)  
[Source Codes](https://drive.google.com/drive/folders/1XT8L-lpN4LGlu10fxsC6HW1YSxR7K-3l?usp=sharing)

### ✅ Conclusion
The analysis revealed:
> Married women aged **26–35 years** from **Uttar Pradesh, Maharashtra, and Karnataka**, employed in **IT, Healthcare, or Aviation**, show the highest purchasing activity in **Food, Clothing, and Electronics**.

This insight helps businesses tailor marketing strategies toward this dominant consumer segment.

---

## 🧾 Author
**Utkarsh Anand**  
📧 Email: [Your Email Here]  
🎓 B.Tech in Computer Science and Engineering  
🏫 Kalinga Institute of Industrial Technology (KIIT)  
🧩 Data Analytics | Python | SQL | Power BI | Machine Learning  

---

## ⚡ License
This project is released under the MIT License — free to use, modify, and distribute with attribution.

---

### 🌐 Tags
`Python` `EDA` `Pandas` `Matplotlib` `Seaborn` `SQLite` `Data Analysis` `Internship` `TATA Steel` `Business Insights`
