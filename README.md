# 🛒 Amazon Sales Data Cleaning Project  

## 📌 Project Overview  
This project focuses on cleaning and preparing raw Amazon sales data for further analysis.  
The dataset contains order details such as product information, customer details, prices, quantities, and shipping details.  

The main goal is to transform *unclean, messy data* into a structured and analysis-ready format.  

---

## 🎯 Objectives  
- Import and inspect the dataset  
- Handle missing values  
- Fix column headers (proper case, spell check, consistency)  
- Remove duplicates  
- Handle outliers in numerical data  
- Convert data types (e.g., dates, amounts, currency)  
- Create derived columns (e.g., Total Value = Qty × Amount)  
- Reset index and finalize cleaned dataset  

---

## 🛠️ Tools & Libraries Used  
- *Python*  
- *Pandas* – data manipulation  
- *NumPy* – numerical operations  
- 

---

## 🔧 Data Cleaning Steps  

### 1. Import & Inspect  
- Loaded CSV into Pandas  
- Displayed dataset shape and first few rows  

### 2. Handling Missing Values  
- Dropped or filled missing values depending on column relevance  
- Example: Missing Promotion IDs ignored (non-critical), Amount handled carefully  

### 3. Fix Column Headers  
- Converted headers to *Proper Case*  
- Renamed inconsistent spellings (e.g., "Cstmr Name" → "Customer Name")  

### 4. Remove Duplicates  
- Checked duplicate rows and removed them  

### 5. Handle Outliers  
- Used *IQR (Interquartile Range)* method  
- Removed extreme values in Amount, Quantity  

### 6. Convert Data Types  
- Converted Date columns to *datetime*  
- Converted Amount and Quantity to *numeric*  
- Standardized Currency (all in INR)  

### 7. Derived Columns  
- Created Total Value = Amount × Quantity  

### 8. Reset Index  
- Reset DataFrame index after cleaning  

---

## 📊 Final Dataset  
- Cleaned dataset is free from duplicates, missing values, and outliers  
- Columns have proper names and data types  
- New derived features added for analysis  

---

## 📂 Project Files  
- amazon_sales.csv → Raw dataset
- ## Dataset
The dataset used in this project can be downloaded from Kaggle:  
[Amazon Sales Report Dataset](https://www.kaggle.com/datasets/mdsazzatsardar/amazonsalesreport)

---

## 🚀 Next Steps (Future Work)  
- Exploratory Data Analysis (EDA) on cleaned data  
- Customer behavior analysis  
- Sales trend visualization  
- Insights for business decisions  

---

✍️ *Author*: Namitha 
📅 *Date*: 27/8/2025
