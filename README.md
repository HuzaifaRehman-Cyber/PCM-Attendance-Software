# PCM AttendPay Pro

**Smart Attendance & Payroll Management System**

PCM AttendPay Pro is a web-based **Attendance & Payroll Management System** developed for managing employee attendance, working hours, leaves, salary calculations, deductions, and monthly reports.

The system is designed to reduce manual attendance calculations and make payroll processing faster, more organized, and less error-prone.

---

## Project Overview

**Project Name:** PCM AttendPay Pro
**Version:** 17-Sep-2026
**Type:** Web Application
**Technology:** HTML, CSS, JavaScript
**Charts:** Chart.js
**Storage:** Browser-based data handling
**Target Use:** Office / Factory / Business Attendance & Payroll Management

---

## Key Features

### Attendance Management

* Import attendance records
* Employee-wise attendance tracking
* Check-In and Check-Out time management
* Working-hours calculation
* Present / Absent / Leave status
* Late arrival tracking
* Monthly attendance records
* Attendance filtering and searching

### Payroll Management

* Employee salary management
* Automatic working-day calculations
* Attendance-based salary calculations
* Leave and absence deductions
* Late/penalty calculations
* Monthly salary summaries
* Employee-wise payroll reports

### Business Rules

The system supports customized attendance rules such as:

* **Monday–Friday:** 9:00 AM – 6:00 PM
* **Full working hours:** 8 hours 45 minutes
* **Saturday:** 9:00 AM – 1:00 PM
* **Saturday full day:** 4 hours
* Saturday attendance can use a configurable multiplier
* 8-hour absence/late calculation can be converted into a leave according to the configured rules
* Salary calculations are based on the configured monthly payroll rules
* Duplicate salary deductions are prevented

---

## Dashboard

The dashboard provides a quick overview of:

* Total Employees
* Present Employees
* Absent Employees
* Leave Count
* Late Employees
* Attendance Percentage
* Payroll Summary
* Monthly Statistics

Charts are used to make attendance and payroll data easier to understand.

---

## Attendance Data

The application can work with attendance data containing information such as:

```text
Name
State
C-In
C-Out
Time
```

This allows attendance records to be processed and converted into useful employee attendance information.

---

## Payroll Data

Salary information can be processed using employee salary records such as:

```text
Employee Name
Grand Total
```

The system combines salary information with attendance rules to generate payroll calculations.

---

## Additional Features

* Employee search
* Date filtering
* Monthly filtering
* Attendance status filters
* Salary reports
* Company reports
* Print reports
* Excel-compatible data handling
* Data import
* File upload support
* Custom attendance overrides
* Configurable working hours
* Configurable closing time
* Penalty multiplier
* Admin controls
* Login / access control
* Permission-based functionality
* Audit trail
* Automatic session logout
* Responsive interface

---

## Attendance Override System

The system supports manual overrides for special attendance situations.

Configurable values include:

```text
Date
Start Time
Required Hours
Closing Time
Penalty Multiplier
```

This makes the system flexible enough to handle different working schedules and exceptional cases.

---

## Technology Stack

| Technology            | Purpose                         |
| --------------------- | ------------------------------- |
| HTML5                 | Application structure           |
| CSS3                  | UI design and responsive layout |
| JavaScript            | Application logic               |
| Chart.js              | Attendance & payroll charts     |
| CSV                   | Attendance data import/export   |
| Excel-compatible data | Reporting and payroll data      |

---

## Project Structure

```text
PCM-AttendPay-Pro/
│
├── index.html
├── README.md
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
└── data/
```

---

## How It Works

### 1. Import Attendance Data

Attendance records are imported into the system.

### 2. Process Attendance

The application analyzes:

* Check-in time
* Check-out time
* Working hours
* Late arrival
* Absence
* Leave
* Working-day rules

### 3. Calculate Payroll

Attendance information is combined with employee salary information.

### 4. Generate Reports

The system generates:

* Attendance reports
* Employee reports
* Monthly summaries
* Payroll reports
* Company-level statistics

### 5. Review & Print

Reports can be filtered, reviewed, and printed for record keeping.

---

## Project Purpose

The main purpose of PCM AttendPay Pro is to demonstrate how a real-world business problem can be converted into a practical software solution.

Instead of manually calculating attendance, working hours, leaves, penalties, and salaries, the system automates these processes through a centralized web application.

---

## Future Improvements

Planned improvements include:

* SQL Server database integration
* Backend API
* Employee management module
* Real-time database synchronization
* Advanced role-based permissions
* Automated salary generation
* PDF payroll reports
* Email notifications
* Cloud deployment
* Backup and restore system
* Advanced audit logs
* Multi-company support

---

## Developer

**Huzaifa Rehman**

BSCS Student | Data Entry & Business Software | Web Development

This project was developed as a practical business software project to explore attendance management, payroll automation, data processing, and web application development.

---

## Project Status

**Current Status:** Working Prototype / Active Development

**Version:** `17-Sep-2026`

The project is continuously being improved with additional business rules, reporting features, security controls, and database functionality.

---

## License

This project is developed for educational, portfolio, and demonstration purposes.
