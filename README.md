# 🧠 Log-Analysis-Python-Tata_Steel_Internship

This repository documents my **Tata Steel Internship Project** on **Log Analysis and Data Analytics using Python**, conducted under the mentorship of **Mr. Anup Kumar (IT Department, TATA Steel Ltd.)** from **22 July 2024 – 24 October 2024**.  
The project explores **data cleaning, log file parsing, analysis, visualization, and database integration** to derive meaningful insights from raw system logs.

---

## 📘 Project Overview

The objective of this project was to **analyze large-scale log data** and extract actionable insights using **Python**.  
This included:
- Parsing and cleaning raw logs  
- Identifying anomalies and performance trends  
- Visualizing user behavior and system activity  
- Storing processed data in a **SQLite** database  
- Generating structured reports for analysis

---

## 🎯 Project Objectives

1. Analyze system and user **log files** to extract insights.  
2. Perform **data cleaning** and manage missing or corrupted entries.  
3. Generate **visual insights** using Matplotlib and Seaborn.  
4. Automate **multi-file processing** for scalability.  
5. Store analyzed results in a **database** for efficient querying.  
6. Export insights to **CSV files** for sharing and reporting.  

---

## 🧩 Methodology

### 1️⃣ Log File Analysis
- Parsed **text-based** and **JSON** logs using Python’s `re` and `json` modules.
- Extracted structured info (timestamps, error codes, user IDs, log levels).
- Cleaned data by removing duplicates, handling missing values, and ensuring correct data types.

### 2️⃣ Data Cleaning & Preprocessing
- Used **pandas** for DataFrame manipulation.
- Handled outliers and formatted timestamps to `datetime` objects.
- Dropped irrelevant columns and null values.

### 3️⃣ Data Analysis & Insights Extraction
- Computed metrics like:
  - **Error frequency**
  - **User activity patterns**
  - **Peak usage times**
- Performed **descriptive statistics** (mean, median, std, etc.) using pandas.

### 4️⃣ Data Visualization
Visualized insights using:
- **Matplotlib** for basic plots  
- **Seaborn** for enhanced visuals  

Key visualizations included:
- 📊 Error frequency bar charts  
- 📈 System usage line graphs  
- 🔥 User activity heatmaps  
- 🥧 Device usage pie charts  

### 5️⃣ Database Integration
- Designed a **SQLite** database to store processed data.
- Created tables for errors, user activity, and usage metrics.
- Implemented **bulk insert** operations for speed and efficiency.

### 6️⃣ Handling Multiple Files
- Automated file iteration using `os` and `glob`.
- Implemented **multiprocessing** for parallel data processing.
- Ensured scalability for future data growth.

---

## 💻 Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| Programming Language | Python |
| IDE / Environment | Jupyter Notebook |
| Data Analysis | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Parsing & Regex | re, json |
| Database | SQLite |
| Utilities | os, glob, multiprocessing |
| Version Control | Git & GitHub |

---

## 📊 Results & Insights

- Most frequent **errors and warnings** identified by type and occurrence.
- Peak **user activity hours** detected via heatmaps.
- **State-wise** and **occupation-wise** purchasing power analyzed.
- Top-performing **product categories**: Food, Clothing, Electronics.
- Target consumer segment:  
  ➤ *Married women (26–35 years), from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation.*

---

## ⚙️ Challenges Faced

1. **Inconsistent Log Formats** – Solved using conditional parsing and regex optimization.  
2. **Corrupted or Missing Data** – Applied validation and fallback mechanisms.  
3. **Performance Bottlenecks** – Optimized memory usage with generators and multiprocessing.  
4. **Database Speed** – Used batch inserts and transactions for faster data handling.  
5. **Complex Regex Patterns** – Modularized and tested patterns iteratively.  

---

## 🧾 Key Takeaways

- Gained strong hands-on experience in **data analytics with Python**.  
- Learned practical handling of **real-world, unstructured log data**.  
- Built **end-to-end automation**, from parsing → analysis → visualization → database.  
- Understood the business value of translating raw data into **actionable insights**.

---

## 📁 Repository Structure

Log-Analysis-Python-Tata_Steel_Internship/
│
├── 📜 DataAnalysis.pdf              # Exploratory Data Analysis code and visuals
├── 📜 TATASteel_Internship.pdf      # Full internship project report
├── 📂 Code_Files/                   # Python source scripts (.py / .ipynb)
├── 📂 Visualizations/               # Graphs & plots generated during analysis
├── 📂 Reports/                      # Final project report & CSV outputs
└── README.md                        # You’re here

---

## 🧠 Conclusion

This project demonstrates how **Python-based data analysis** can transform unstructured log data into valuable business insights.  
The findings help identify **target customer segments** and **optimize data-driven decision-making**.  
The experience not only sharpened my analytical and technical skills but also built a solid foundation for **real-world data science applications**.

---

## 🙏 Acknowledgement

I would like to thank **Mr. Anup Kumar (IT Department, Tata Steel)** for his constant guidance, and the **Tata Steel team** for their support throughout the internship.  
This project was a cornerstone in my journey toward becoming a proficient **data analyst and Python developer**.

---

## 👤 Author

**Name:** Utkarsh Anand  
**Vocational Training No:** VT20245542  
**Institution:** Kalinga Institute of Industrial Technology (KIIT)  
**Mentor:** Mr. Anup Kumar (IT Department, Tata Steel)  
**Internship Duration:** 22 July 2024 – 24 October 2024  

---

## 🔗 References & Resources

- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [pandas Documentation](https://pandas.pydata.org/)
- [Python Official Docs](https://docs.python.org/3/)
- [SQLite Docs](https://www.sqlite.org/docs.html)

---

> “Data tells stories — you just need to learn the language it speaks.” 🧩
