# 🚀 Employee Management System (EMP_MGMT_SYSTEM)

## 💡 Project Overview
The **Employee Management System** is a database-driven application designed to manage employee records in an organization. It provides a simple yet powerful solution for storing, retrieving, updating, and deleting employee information.  
This project focuses on the use of **SQL (MySQL Workbench)** to handle structured data and demonstrates core database management operations.

---

## ✅ Features
- **CRUD Operations** (Create, Read, Update, Delete) on Employee records  
- Manage key employee attributes:  
    - Employee Number (EMPNO)  
    - Employee Name (ENAME)  
    - Job Designation (JOB)  
    - Manager ID (MGR)  
    - Hire Date (HIREDATE)  
    - Salary (SAL)  
    - Commission (COMM)  
    - Department Number (DEPTNO)  
- Maintain **Department Records** with department number, name, and location  
- Implement **foreign key relationships** (EMP → DEPT)  
- Use advanced SQL queries for:  
    - Data filtering  
    - Aggregations (e.g., average salary per department)  
    - Hierarchical queries (employees & managers)  
    - Sorting, searching by attributes  
- Handle NULL values and constraints (e.g., NOT NULL, UNIQUE)  
- Schema design with proper **primary and foreign key constraints**

---

## 🛠️ Tech Stack
- **Database**: MySQL (via MySQL Workbench)  
- **SQL Concepts**:  
    - DDL (CREATE TABLE, ALTER TABLE, DROP TABLE)  
    - DML (INSERT, UPDATE, DELETE)  
    - DCL (GRANT, REVOKE)  
    - TCL (COMMIT, ROLLBACK)  
    - Complex Queries (JOINS, Subqueries, Aggregations, Conditions)  

---

## 📂 Project Structure
EMPLOYEE_MANAGEMENT_SYSTEM/
│
├── schema.sql # Table creation scripts
├── data.sql # Sample data inserts
├── queries.sql # Example complex SQL queries
├── ER_Diagram.png # Visual ER diagram of EMP & DEPT
├── README.md # Project descriptio
