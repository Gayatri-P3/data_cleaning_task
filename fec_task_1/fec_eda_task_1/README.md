# FEC Data Analysis & Cleaning

## 📊 Project Overview
This project involves processing and cleaning a dataset from the **Federal Election Commission (FEC)** containing **1,000,000 rows** and **16 columns**. The goal was to transform raw, messy financial records into a structured format ready for meaningful insights.

## 🛠 Key Challenges & Solutions
* **Data Volume:** Handled 10 lakh rows efficiently using optimized Pandas data types to reduce memory usage.
* **Data Integrity:** Identified and handled missing values, duplicate entries, and inconsistent naming conventions.
* **Standardization:** Cleaned and formatted dates, currency values, and ZIP codes for geographical analysis.

## 🧹 Data Cleaning Process
1.  **Memory Optimization:** Downcasted numeric columns and converted object types to `category`.
2.  **Handling Nulls:** Imputed or removed missing values based on financial impact.
3.  **Outlier Detection:** Investigated extreme contribution amounts for data entry errors.
4.  **Feature Engineering:** Extracted time-based information (Month/Year) from raw timestamps.

## 🔍 Insights Extracted
* **Top Contributors:** Identified the top 10 individual and organizational donors.
* **Temporal Trends:** Analyzed contribution volumes leading up to key election dates.
* **Geographic Distribution:** Mapped donations by state/region.

## 📁 Repository Structure
```text
├── data_analysis/
│   ├── cleaned_data_sample.csv  
│   ├── fec_cleaning_logic.py    
│   └── analysis_notebook.ipynb  
├── README.md
└── requirements.txt 
