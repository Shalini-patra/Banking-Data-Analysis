# 🏦 Banking Risk Analytics Project

## 📌 Overview
This project focuses on developing a basic understanding of **risk analytics** in **banking and financial services**, and how data can be used to **minimize the risk of losing money while lending to customers**.

The analysis was done using **Python**, **SQL**, and **Power BI** to:
- Perform **Exploratory Data Analysis (EDA)**
- Segment customers based on income and total wealth
- Identify risky customers and important KPIs
- Visualize results through an **interactive Power BI dashboard**

---

## 🛠 Tools & Technologies
- **Python (Jupyter Notebook)** – Data exploration & preprocessing  
- **SQL (MySQL)** – Data storage & querying  
- **Power BI** – Dashboard creation & KPI visualization  
- **DAX** – Calculated columns, measures, and advanced aggregations  

---

## 📂 Dataset
- **Source**: Banking sample dataset  
- **Includes**: Customers, accounts, loans, deposits, transactions  
- **Key Fields**: Income, Wealth, Loan Amount, Deposit Amount, Risk Score  

---

## 📊 Project Workflow

### 1️⃣ Importing Data into MySQL
- Created a database and imported CSV files into MySQL tables.
- Verified schema and relationships between tables.
- Indexed key columns for faster query performance.

### 2️⃣ Exploratory Data Analysis (EDA) in Python
- Used **Pandas**, **Matplotlib**, and **Seaborn** to:
  - Analyze customer income and wealth distribution  
  - Explore correlation between income/wealth and loan risk  
  - Classify customers into **risk categories**  

### 3️⃣ Data Modeling in Power BI
- Connected Power BI directly to the MySQL database.
- Created **calculated columns** using DAX:
  - `Income Band`
  - `Risk Status`
  - `Time Frame`
  - `Fee Rate`
- Built **measures** for:
  - Total Loans
  - Total Deposits
  - Total Fees

### 4️⃣ Dashboard Development
Developed a **4-page interactive dashboard**:
1. **Customer Segment Analysis** – Income & wealth-based segmentation, risk levels  
2. **Deposit Analysis** – Trends & high-value depositors  
3. **Loan Analysis** – Loan distribution & high-risk customers  
4. **Summary Page** – Key KPIs & overall financial performance  

---

## 📌 Key Insights
- Top **5 high-income clients** identified  
- Top **5 loan holders** ranked by loan amount  
- Top **5 investment advisors** with the highest risky customers found  
- Loan risk varies significantly with **income** and **total wealth**  

---

## 📷 Dashboard Preview
> 🔗 **View Interactive Dashboard**: [Click Here](https://app.powerbi.com/groups/c60e69f0-a2d4-462a-b8d4-74311bbdc461/reports/9149e118-45db-4d88-ac19-0f52acf007cf/3618ada0522c1e08de42?experience=power-bi)

---

## 🚀 How to Run This Project
1. **Clone this repository**  
2. **Import the dataset into MySQL**  
3. **Run the Python EDA notebook** to explore the data  
4. **Open the Power BI file** and connect it to the MySQL database  
5. Explore the **interactive dashboard**  

---

## 🧠 Skills Demonstrated
- SQL database creation & querying  
- Data exploration & visualization in Python  
- Data modeling and transformation in Power BI  
- Creating DAX measures & calculated columns  
- Risk classification & customer segmentation  
- Dashboard storytelling & KPI presentation  

---

## 📜 License
This project is licensed under the MIT License.
