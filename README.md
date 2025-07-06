# 📦 Reusable SQL Blocks – Stored Procedure & Function

This mini SQL task focuses on creating **reusable SQL logic** using a **stored procedure** and a **user-defined function** in a MySQL database environment.

---

## 🎯 Objective

To learn how to modularize SQL logic using stored procedures and functions that can be reused across multiple queries or operations.

---

## 🛠️ Tools Used

- MySQL Workbench ✅ *(Recommended)*
- DB Browser for SQLite ❌ *(Note: SQLite does not support procedures/functions)*

---

## 📋 Task Description

### ✅ Deliverables

- At least **one stored procedure** using `CREATE PROCEDURE`
- At least **one user-defined function** using `CREATE FUNCTION`
- Sample call or usage of both

### 🧠 Hints / Guide

- Use parameters and conditional logic (`IF`, `DECLARE`, `SELECT INTO`)
- Example Procedure: Borrow a book **only if** it’s in stock
- Example Function: Calculate fine based on `due_date` and `return_date`

---

## 📌 Outcome

By completing this task, you will:

- Understand how to write modular SQL logic
- Be able to encapsulate logic in procedures and functions
- Improve maintainability of your SQL code

---

## 🚀 Sample Use Cases (Examples)

> 💡 These are **only examples** you can implement during the task.

- `CALL BorrowBook(1, 2, '2024-07-01', '2024-07-10');`  
- `SELECT CalculateFine('2024-07-10', '2024-07-15');`

---

## 📁 File Structure

readme
