# 🗂️ Batch CSV & Excel Processor

## 📌 Overview
**Python CLI program** to automatically **clean, aggregate, and summarize multiple CSV and Excel datasets**.  

Demonstrates **pandas, OpenPyXL, and automation best practices** in a structured workflow suitable for data analysts and business intelligence.

---

## ⚙️ Workflow

### 1️⃣ System Recognition
- **Domain:** Batch data cleaning and summarization.  
- **Goal:** Automatically process multiple CSV and Excel files for analysis.  
- **Constraint:** Support large datasets and maintain data integrity.

### 2️⃣ Data Collection
- Input: All `.csv` and `.xlsx` files in a specified folder.  
- Output folder automatically created if it doesn't exist.

### 3️⃣ Data Cleaning
- Remove fully empty rows and columns.  
- Fill missing values with `0` (or other defaults).  
- Ensure data consistency for downstream processing.

### 4️⃣ Exploratory Analysis
- Generate descriptive statistics for numeric and categorical columns.  
- Summaries are transposed for readability.  
- Track progress and log processed files.

### 5️⃣ Visualization
- Optional: Export summaries to Excel/CSV for reporting.  
- Progress and logs displayed in console.  

### 6️⃣ Insights / Output
- Cleaned datasets saved to the output folder.  
- Summary reports saved separately.  
- Enables **fast insights** across multiple datasets without manual effort.

---

## 🚀 Key Features

| Feature | Technique / Concept |
|---------|-------------------|
| Batch processing | Automatically loop through CSV/XLSX files |
| Data cleaning | Remove empty rows/columns, fill missing values |
| Data summarization | Descriptive statistics for numeric and categorical columns |
| Export results | Save cleaned data and summaries to output folder |
| Automation | Modular Python functions, progress logging |
| Scalable | Supports large batches efficiently |

---

## 🛠️ How to Run

1. Place your `.csv` and `.xlsx` files in the `data` folder.  
2. Run the script:

```bash
python batch_processor.py
