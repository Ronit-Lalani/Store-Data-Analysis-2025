# Store-Data-Analysis-2025
Sales data analysis project using Excel and Power BI / Tableu

# 📊 Store Data Analysis (2025)

## 📌 Objective
To analyze store sales data for 2025 and uncover insights about customer behavior, product performance, and sales trends to support business growth in 2026.

---

## 🛠️ Tools Used
* Microsoft Excel (Data Cleaning, Pivot Tables)
* Power BI / Tableau (Dashboard & Visualization)

---

## 🔍 Key Analysis
* Sales performance by category and channel
* Customer segmentation (Gender, Age)
* Regional sales distribution
* Monthly sales trends

---

## 📈 Key Insights
* Women customers contribute the majority of sales
* Ethnic wear categories (Kurta, Saree, Blouse) are top-performing
* Amazon and Myntra are leading sales channels
* Maharashtra is the highest revenue-generating state

---

## 🧹 Data Cleaning & Preparation

The raw dataset contained inconsistencies, missing values, and formatting issues. The following steps were performed to prepare the data for analysis:

* Removed duplicate records based on Order ID
* Standardized categorical columns (Gender, Channel) to ensure consistency
* Handled missing values:

  * Replaced missing Gender, City, and State values with "Unknown"
  * Imputed missing Age values using average
  * Removed records with missing critical fields such as Amount and Date
* Cleaned and standardized postal code column by replacing invalid entries (e.g., '0', 'n/a', 'xxxx') with "Unknown"
* Converted Amount column from text (currency format) to numeric values
* Fixed date format inconsistencies and converted all entries into standard date format
* Extracted month from date column for time-based analysis
* Removed logically inconsistent records (e.g., Delivered orders with zero quantity)
* Cleaned text fields using TRIM and PROPER functions to remove extra spaces and standardize formatting


---

## 📊 Dashboard
(Add dashboard screenshot here)

---

## 🚀 Business Recommendations
* Focus on targeted marketing strategies for key customer segments
* Invest more in top-performing sales channels
* Introduce bundled offers to increase average order value
* Improve data quality for better decision-making

---

## 📁 Project Structure
* data/ → Raw dataset
* excel/ → Data cleaning and pivot analysis
* dashboard/ → Power BI / Tableau dashboard
* images/ → Dashboard screenshots

---

## 🙋‍♂️ Author

Ronit Lalani


