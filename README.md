🏠 Nashville Housing Data Cleaning (SQL Project)
📌 Overview

This project focuses on cleaning and transforming a real-world Nashville housing dataset using SQL. The raw dataset contained missing values, inconsistent formatting, and duplicate records that made it unsuitable for analysis.

The goal was to create a structured, clean dataset ready for data analysis and visualization.

⚙️ Tools Used

SQL (SQL Server / MySQL — update this)

Excel (optional, if used)

🧹 Data Cleaning Process

The following steps were performed:

Standardized date format for SaleDate

Filled missing PropertyAddress values using self-joins

Split address columns into:

Street Address

City

State

Converted SoldAsVacant values (Y/N → Yes/No)

Removed duplicate records using ROW_NUMBER()

Dropped unused or redundant columns

📊 Before vs After

Raw data contained null values, duplicate rows, and inconsistent formats

Cleaned dataset is structured, consistent, and analysis-ready

(Add screenshots here if you have them)

🚀 Outcome

The dataset is now:

Clean and standardized

Free of duplicates

Ready for visualization (Tableau / Power BI) or further analysis
