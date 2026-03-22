# 🏠 Nashville Housing Data Cleaning (SQL Project)

## 📌 Overview
This project focuses on cleaning and transforming a real-world Nashville housing dataset using SQL. The raw dataset contained missing values, inconsistent formatting, and duplicate records that made it unsuitable for analysis.

The goal of this project was to prepare the dataset for downstream analytics by applying industry-standard data cleaning techniques.

---

## ⚙️ Tools Used
- SQL (SQL Server)
- Excel 

---

## 🧹 Data Cleaning Process

The following transformations were performed:

- Standardized date format for `SaleDate`
- Filled missing `PropertyAddress` values using self-joins
- Split address columns into:
  - Street Address
  - City
  - State
- Normalized categorical values (`SoldAsVacant`: Y/N → Yes/No)
- Identified and removed duplicate records using `ROW_NUMBER()`
- Removed unused or redundant columns

---

## 📊 Before vs After

**Before:**
- Missing values
- Duplicate records
- Inconsistent formatting

**After:**
- Clean and structured dataset
- Consistent formatting
- Ready for analysis or visualization


---

## 🚀 Outcome

The dataset is now:
- Clean and reliable  
- Structured for querying  
- Ready for use in tools like Tableau or Power BI  


## 📬 Contact
If you have any questions or feedback, feel free to reach out!
