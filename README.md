# 📦 U.S. Exports & Imports Analysis (2022–2024)

## 📌 Overview  
This project analyzes U.S. international exports and imports from 2022 to Q2 2024 using data from the **U.S. Bureau of Economic Analysis (BEA)**. The goal is to study trends in investment income, general merchandise, industrial supplies, and financial sectors through a complete data pipeline: collection, cleaning, storage, analysis, visualization, and interpretation.

---

## 🎯 Objectives  
- Analyze changes in U.S. trade between 2022 and 2024  
- Clean and standardize raw BEA datasets  
- Store and query data using **Google BigQuery**  
- Build interactive dashboards using **Looker Studio**  
- Interpret trends across exports, imports, and investment categories  

---

## 🗂️ Data Sources  
**U.S. Bureau of Economic Analysis (BEA):**  
International Transactions & U.S. Trade Data  
(2022 → Q2 2024)

Dataset includes:  
- Investment income  
- Direct & portfolio investment  
- Capital goods imports  
- Industrial supplies  
- Manufacturing and financial sector indicators

---

## 🧹 Data Processing  
Tools: **OpenRefine**, **Google Sheets**

Steps:  
- Convert text to numeric fields  
- Remove duplicates and blank rows  
- Handle missing values  
- Standardize formatting  
- Prepare final cleaned dataset for BigQuery ingestion

---

## 🗄️ Data Storage  
- Stored in **Google Cloud BigQuery**  
- Enables fast querying, scalable storage, and SQL-based analysis

---

## 🧠 Data Analysis  
Used **BigQuery SQL** to:  
- Calculate year-over-year changes  
- Compare Q1 and Q2 of 2024  
- Analyze sector-specific performance  
- Use CTEs to group categories (e.g., investment income)  
- Summarize import vs export values across sectors

---

## 📊 Data Visualization  
Tools: **Looker Studio + BigQuery**

Insights include:  
- Investment income is the dominant export category in both 2022 and 2023  
- Capital goods lead overall imports, consistently exceeding $200B per quarter  
- Financial sectors show strong growth due to global market trends  
- Manufacturing remains volatile due to supply chain disruptions  
- Industrial supplies remain stable with high export value  

---

## 📌 Conclusion  
This analysis highlights key economic shifts in U.S. international trade, revealing strong export performance in investment income and rising imports in capital goods. BigQuery and Looker Studio enabled efficient querying, visualization, and interpretation of multi-year BEA datasets.

---

## 👥 Team  
- **Moulya Reddygari Bhupal** – Data Cleaning, Visualization   
- Akhil Panakanti – Data Analysis & Visualization  
- Quynh Nguyen – Data Storage & Visualization  

---

## 📬 Contact  
**Moulya Reddygari Bhupal**  
📧 Email: moulyarb02@gmail.com  
🔗 GitHub: https://github.com/Moulya002  
🔗 LinkedIn: https://www.linkedin.com/in/moulyarb/
