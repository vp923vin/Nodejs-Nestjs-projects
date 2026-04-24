# 🚀 Node.js / NestJS Projects

A collection of backend projects built using **Node.js** and **NestJS**, focusing on real-world business systems and scalable architecture.

---

## 📌 Project List

### 🔐 1. Login System

* Basic authentication using email/password
* JWT-based authentication
* Secure password hashing (bcrypt)

---

### 🔐 2. Advanced Login System

* Access & Refresh tokens
* Role-Based Access Control (RBAC)
* Permissions (Admin / HR / Employee)
* Guards, Interceptors, Middleware (NestJS)

---

### ⏱️ 3. Attendance & Punch In/Out System

A real-world employee tracking system.

#### Features:

* Punch In / Punch Out with timestamps
* Working hours calculation
* Late / early detection
* Break tracking
* Prevent duplicate punch-in
* Auto punch-out (cron job)
* Timezone handling

#### Core Entities:

* User
* Attendance
* Shift
* Logs

---

### 💰 4. Payroll Management System

Handles employee salary processing based on attendance.

#### Features:

* Salary structure (Basic, HRA, Allowances)
* PF, ESI, Tax deductions
* Automatic salary calculation
* Payslip generation (PDF)

#### Formula:

```
Net Salary = Gross Salary - (PF + Tax + Other Deductions)
```

---

### 🧾 5. Leave Management System

* Apply for leave
* Approval / rejection workflow
* Leave balance tracking
* Leave types (Sick, Casual, Paid)

---

### 📊 6. Admin Dashboard & Reports

* Attendance reports
* Payroll reports
* Employee insights
* Export data (CSV / Excel)

---

## 🧠 Architecture (NestJS)

### Modules:

```
AuthModule
UserModule
AttendanceModule
PayrollModule
LeaveModule
ReportModule
```

---

## ⚙️ Tech Stack

* **Backend:** NestJS (Node.js)
* **Database:** PostgreSQL
* **ORM:** Prisma
* **Cache (optional):** Redis
* **Queue (optional):** Bull (for background jobs)

---

## 🧩 Design Patterns & Best Practices

* Repository Pattern (DB abstraction)
* Service Layer (business logic separation)
* DTO + Validation (data integrity)
* Guards (authentication & authorization)
* Cron Jobs (automation like payroll & auto punch-out)

---

## 🔥 Advanced Features (Future Enhancements)

* Face recognition for attendance
* Biometric device integration
* Multi-tenant system (multiple companies)
* Audit logs (tracking changes)
* Real-time dashboard (WebSockets)

---

## 📈 Development Approach

Build the system in phases:

1. Authentication & User Management
2. Attendance System
3. Payroll System
4. Leave & Reporting

Each phase should be independently functional and deployable.

---

## 🎯 Goal

To build scalable, production-ready backend systems using **clean architecture**, **SOLID principles**, and **modern development practices**.

---

## 📂 Folder Structure (Example)

```
src/
 ├── auth/
 ├── users/
 ├── attendance/
 ├── payroll/
 ├── leave/
 ├── reports/
 ├── common/
 └── config/
```

---

## 🤝 Contribution

Feel free to fork, improve, and contribute to these projects.

---

## 📄 License

This project is open-source and available under the MIT License.
