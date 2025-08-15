PaySync – Distributed Salary Management System
Description

PaySync is a PL/SQL-based salary management solution powered by a distributed database.
It simulates a real-world payroll system with role-based access control to ensure secure and efficient handling of salary-related operations.
The system enables administrators, accountants, and employees to manage and access payroll information seamlessly.

Features
Admin / HR

Add and update employee records.

Assign salary structures.

Manage department details.

Accountant

Process salary payments.

Maintain financial transaction records.

Generate payroll and financial reports.

Employee

View salary slips and payment history.

Access personal information securely.

Additional Highlights

Role-based access control for proper segregation of duties.

Automated and manual report generation for payroll analysis.

Technologies Used

PL/SQL

Distributed Database

Database Schema
Tables

Employees (employee_id, name, department, position, salary)

Departments (department_id, name, head)

Salaries (salary_id, employee_id, amount, date_paid)

Accounts (account_id, employee_id, salary_id, transaction_date)

Supporting tables for role management and reporting

Key Advantages

Streamlined payroll operations.

Enhanced data security via role-based permissions.

Scalable architecture for organizations of various sizes.
