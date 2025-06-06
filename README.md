# 🧠 Smart Biometric Attendance System

A **PHP & MySQL-based biometric attendance system** that automates student attendance using biometric data inputs. This system offers role-based dashboards for faculty and students, real-time data syncing with biometric sensors, and insightful attendance reporting.

---

## 🚀 Project Highlights

- 🔐 **Biometric Integration**: Real-time attendance tracking using biometric sensor input via `sensor_data.php`.
- 📊 **Role-Based Dashboards**: Separate UI and functionality for students and faculty.
- 🗂️ **Database-Driven**: Attendance data stored and retrieved using structured MySQL queries.
- 🌐 **Web-Based Access**: Accessible through browsers, optimized for deployment in local LAN or XAMPP/WAMP stack.
- 🛠️ **Customizable Auth**: Includes prebuilt user login system with sample credentials.

---

## 📁 Tech Stack

| Category       | Tools Used            |
|----------------|-----------------------|
| Backend        | PHP                   |
| Frontend       | HTML, CSS, JS         |
| Database       | MySQL (via phpMyAdmin)|
| Hosting        | Apache (XAMPP/WAMP)   |
| Data Source    | Biometric Sensor      |

---

## 🔧 How to Run the Project

> Works on **Windows (XAMPP/WAMP)** or **Linux (LAMP stack)** environments.

### 1️⃣ Setup Project Files
- Extract the `smart_attendance` folder and place it in:
  - Windows: `C:/xampp/htdocs/` or `C:/wamp/www/`
  - Linux: `/var/www/html/`

### 2️⃣ Configure Database
- Open **phpMyAdmin** and create a new database named:
```

biometric

````
- Import the `biometric.sql` file provided in the root directory.

### 3️⃣ Set Database Credentials
- Open `connection.php` and update your MySQL credentials:
```php
$username = "your_phpmyadmin_username";
$password = "your_password";
````

### 4️⃣ Run the Server

* Start Apache and MySQL from XAMPP/WAMP control panel.
* Open your browser and navigate to:

  ```
  http://localhost/smart_attendance-master/
  ```

---

## 👤 Sample Credentials

| Role    | Username                                                      | Password |
| ------- | ------------------------------------------------------------- | -------- |
| Faculty | [mukeshbathre@gcekjr.ac.in](mailto:mukeshbathre@gcekjr.ac.in) | 09876    |

---

## 📂 Key Files Overview

| File                    | Purpose                                     |
| ----------------------- | ------------------------------------------- |
| `index.php`             | Login and entry point                       |
| `sensor_data.php`       | Accepts biometric data from external sensor |
| `dashboard.php`         | Main dashboard redirection logic            |
| `faculty_dashboard.php` | Faculty-specific dashboard                  |
| `student_dashboard.php` | Student-specific dashboard                  |
| `connection.php`        | Database connection configuration           |
| `biometric.sql`         | Database schema and sample data             |

---

## 🧠 Unique Selling Points (USP)

* 📡 **IoT-Ready**: Built-in PHP handler for remote biometric data transfer.
* 📊 **Comprehensive Reporting**: Attendance report by subject and date.
* 👥 **Multi-User Support**: Custom interfaces and logic for student and faculty users.
* 📚 **Academic Integration**: Tailored for educational institutions to reduce manual overhead.

---

## 🔄 Basic Git Usage Guide

```bash
# Pull latest changes
git pull

# Check status
git status

# Stage all files
git add .

# Or add specific files
git add sensor_data.php

# Commit with message
git commit -m "sensor_data script updated"

# Push changes
git push
```

---
