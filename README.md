# 💰 PaySync – Distributed Salary Management System

> **Efficient. Secure. Scalable.**  
> A PL/SQL-based payroll management system built on a distributed database with role-based access control.

---

## 📌 Overview
**PaySync** is a complete payroll management solution that simulates a real-world salary system.  
With **role-based access control**, it ensures secure handling of salary information for administrators, accountants, and employees.  
Designed for scalability and reliability, PaySync offers smooth payroll processing, data security, and insightful reporting.

---

## 🚀 Features

### 👨‍💼 Admin / HR
- Add & update employee details.
- Assign salary structures.
- Manage departments.

### 📊 Accountant
- Process salary payments.
- Maintain transaction history.
- Generate payroll and finance reports.

### 👤 Employee
- View salary slips.
- Check payment history.
- Access personal details securely.

### 🔒 Security
- Role-based access control to segregate responsibilities.
- Secure database operations with PL/SQL procedures.

---

## 🛠️ Technologies Used
- **PL/SQL**
- **Distributed Database Architecture**

---

## 🗄️ Database Schema

| Table Name   | Columns |
|--------------|---------|
| **Employees** | `employee_id`, `name`, `department`, `position`, `salary` |
| **Departments** | `department_id`, `name`, `head` |
| **Salaries** | `salary_id`, `employee_id`, `amount`, `date_paid` |
| **Accounts** | `account_id`, `employee_id`, `salary_id`, `transaction_date` |
| *Additional Tables* | Role management, reports |

---

## 📈 Key Benefits
- ✅ Automated & accurate payroll processing  
- ✅ Improved data security  
- ✅ Role-based permissions  
- ✅ Scalable for organizations of any size  


---

### ⭐ If you like this project, give it a star on GitHub!
