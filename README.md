# **Data Analytics Internship - Assignment 1**
**Excel Functions, Pivot Tables & SQL Queries**

## **Project Overview**
This repository contains the deliverables for **Assignment 1** of the Data Analytics Internship. The project covers data manipulation, conditional formatting, statistical aggregations, chart visualizations, pivot tables, and relational database queries using SQL.


## **Tasks Summary**

### **Task 1: Excel Formatting, Functions & Charts**
- **Dataset Setup**: Cleaned and structured 15 sales records (`sales_data.xlsx`).
- **Formatting**: Applied currency formatting (INR `₹`), date formatting (`DD-MMM-YYYY`), headers styling, and grid borders.
- **Formulas & Calculations**:
  - `total_amount` (`=E2*F2`)
  - `Bonus` (`=IF(H2>50000, "High", "Normal")`)
  - Aggregations: `SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNTIF`, and `SUMIF`
- **Visualizations**:
  - Bar Chart: Product Names vs. Total Amount
  - Pie Chart: Total Revenue Share by Department
  - Line Chart: Sale Date vs. Total Amount

### **Task 2: Pivot Tables & Pivot Charts**
- **Pivot Table 1**: Total Revenue grouped by Department.
- **Pivot Table 2**: Total Revenue grouped by Department and Employee.
- **Pivot Table 3**: Quantity sold per Product matrix across Departments.
- **Pivot Chart**: Dynamic Bar Chart representing departmental revenue distribution.
- **Slicer Integration**: Interactive Department slicer for real-time data filtering.

### **Task 3: SQL Queries & Database Management**
Executed on relational schema containing `employees` and `sales` tables.

#### **Key SQL Capabilities Demonstrated:**
- **Filtering & Sorting**: `WHERE`, `ORDER BY`, `BETWEEN`
- **Aggregations & Grouping**: `GROUP BY`, `COUNT()`, `AVG()`, `HAVING`
- **Relational Joins**: `INNER JOIN` across sales and employee records
- **Subqueries**: Conditional filtering against aggregate metrics
- **CRUD Operations**: Data modification using `INSERT`, `UPDATE`, and `DELETE`


## **Tools & Technologies**
- **Spreadsheets**: Microsoft Excel / Google Sheets
- **Database / Query Tools**: SQL (MySQL / SQLite Online / OneCompiler)
- **Documentation**: Markdown, MS Word / PDF
