# Salary Management System

## Description
Salary Management System is a PL/SQL-based project built using a distributed database.  
It simulates a real-world payroll system with **role-based access** and allows administrators, accountants, and employees to manage and view salary information effectively.

## Features
- **Admin/HR:** Add/update employee records, assign salaries, manage departments.
- **Accountant:** Process salary payments, maintain financial records, generate reports.
- **Employee:** View salary slips, personal information, and payment history.
- Role-based access control ensures proper segregation of duties.
- Generate various reports for better payroll management.

## Technologies Used
- PL/SQL
- Distributed Database

## Database Schema
- **Employees** (employee_id, name, department, position, salary)
- **Departments** (department_id, name, head)
- **Salaries** (salary_id, employee_id, amount, date_paid)
- **Accounts** (account_id, employee_id, salary_id, transaction_date)
- **Other supporting tables** for role management and reports

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SalaryManagementSystem.git
