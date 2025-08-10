# 🏦 Banking Risk Analytics Project

## 📌 Overview
This project explores **risk analytics** in the **banking and financial services sector**.  
The main goal was to understand **how data is used to minimize the risk of losing money** when lending to customers.

The project uses **Python**, **SQL**, and **Power BI** to perform:
- **Exploratory Data Analysis (EDA)**
- **Risk classification**
- **Customer segmentation**
- **KPI tracking** via interactive dashboards

---

## 🛠 Tools & Technologies
- **Python** (Jupyter Notebook) → Data exploration & preprocessing  
- **SQL** (MySQL) → Storing and querying structured banking data  
- **Power BI** → Interactive dashboard creation and KPI visualization  
- **DAX** → Calculated columns, measures, and advanced aggregations

---

## 📂 Dataset
- **Source**: Banking sample dataset  
- **Size**: Multiple tables including `customers`, `accounts`, `transactions`  
- **Key Fields**: Income, Wealth, Loan Amount, Deposit Amount, Risk Score

---

## 📊 Project Workflow

### **1. Data Import into MySQL**
- Created a **banking database** in MySQL.
- Imported CSV dataset into MySQL using:
```sql
LOAD DATA INFILE 'bank_data.csv'
INTO TABLE customers
FIELDS TERMINATED BY ','
LINES TERMINATED BY '\n'
IGNORE 1 ROWS;
