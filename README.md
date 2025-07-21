# HR-Dataset-Analysis
Performed Data Analysis in SQL on HR Dataset using MySQL Workbench

# HR Data Analysis in SQL
This project showcases the analysis of an **HR dataset** using **MySQL**. The goal is to derive useful business insights such as employee attrition rate, age distribution, departmental performance, and more by writing optimized SQL queries.

---
## 📁 Database Setup

```sql
CREATE DATABASE hrdata;
USE hrdata;
```

## 📌 Table Used

* `employees` – Contains detailed records of employee demographics, work history, performance, and salary.
---

## 📊 Key Insights & Queries

### ✅ Basic Employee Stats

* **Total Employees**
* **Total Old Employees (Terminated)**
* **Total Current Employees**
* **Average Salary**
* **Average Age**
* **Average Years in Company**

### 🔄 Employee Status and Attrition

* Added a new column `EmployeeCurrentStatus` to identify if an employee is currently active.
* Calculated the **Attrition Rate** using this column.

### 🧾 Data Cleanup & Formatting

* Converted date columns (`DOB`, `DateOfHire`, `LastPerformanceReview_Date`) to proper `DATE` format.
* Changed `salary` column to `DECIMAL(10,2)` for precision.
* Filled null/empty values in `DateOfTermination` with `'Currently Working'`.

### 📈 Distribution Reports

* **Marital Status Distribution**
* **Department-Wise Employee Count**
* **Position Distribution**
* **Manager-Wise Headcount**
* **Performance Score Breakdown**
* **State-wise Employee Count**
* **Gender Distribution**

### 💸 Salary Analysis

* **Salary Range Distribution**
* **Average Salary by Department**
* **Salary Distribution by Gender**

### 📅 Age and Experience

* Added and populated a new column `age`.
* Generated **Age Range Distribution**
* **Average Years in Company**

### ⚠️ Termination Analysis

* **Termination Reasons and Counts**
* **Terminations by Marital Status**

### ⛔ Absence and Performance

* Total Absences by Department
* Average Absence by Performance Score

### 🧑‍💼 Recruitment Source

* Employee count grouped by `RecruitmentSource`.
---

## 🛠️ Technologies Used

* MySQL
* SQL Workbench / Any RDBMS GUI
* Structured Query Language (SQL)

---

## 📌 How to Run

1. Clone the repository
2. Import the dataset into MySQL
3. Execute the SQL script step-by-step
4. Use `SELECT` queries to view the insights

---

## 🙌 Acknowledgements

This project is part of a self-learning and exploratory data analysis initiative using real-world HR datasets.

---
