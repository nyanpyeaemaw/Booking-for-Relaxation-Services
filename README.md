# 🌿 Aura of Akeri

**Online Reservation System for Spa, Yoga & Sauna Services**

## 📌 Project Overview

**Aura of Akeri** is a **web-based online reservation system** developed using **PHP and MySQL** that streamlines the booking process for **spa, yoga, and sauna services** across multiple branches.

The system provides a convenient platform for users to explore services, select preferred branches, choose packages, and book appointments at suitable dates and times. It also supports **role-based management** for branch administrators and a head administrator.

This project is developed based on a formal **Software Requirement Specification (SRS)** and follows structured software engineering principles.

---

## 🎯 Project Objectives

* Simplify the booking process for relaxation services
* Improve customer experience through an easy-to-use web interface
* Reduce administrative workload for service providers
* Enable centralized management of branches, users, and services
* Provide a scalable and organized reservation system

---

## 👥 System Actors & Roles

### 👤 User (Customer)

* Register and log in securely
* Browse available services and branches
* Select service packages, date, and time
* Book services and view booking history
* Cancel bookings if needed

### 🧑‍💼 Branch Admin

* Log in to branch admin dashboard
* Manage service packages of their assigned branch
* Update package details and availability

### 🧑‍💻 Head Admin

* Manage branch admins
* Manage branches
* Manage users
* Oversee the overall system (excluding bookings)

---

## ⚙️ Core Functional Features

* User registration & authentication
* Role-based login (User / Branch Admin / Head Admin)
* Service selection (spa, yoga, sauna)
* Branch selection
* Package selection with date & time
* Online booking confirmation
* Booking history management
* Admin management (users, branches, admins, packages)

---

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL / MariaDB
* **Server:** Apache (XAMPP)
* **Development Tools:** VS Code
* **Protocol:** HTTP / HTTPS
* **Platform:** Web-based (Cross-browser)

---

## 🖥️ System Requirements

### Server-Side

* Operating System: Microsoft Windows Server
* Web Server: Apache HTTP Server
* Backend Language: PHP
* Database Server: MySQL / MariaDB

### Client-Side

* Web Browsers:

  * Google Chrome
  * Mozilla Firefox
  * Microsoft Edge
  * Opera

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/aura-of-akeri.git
   ```
2. Move the project folder to:

   ```
   XAMPP/htdocs/
   ```
3. Start **Apache** and **MySQL** in XAMPP
4. Import the database using **phpMyAdmin**
5. Open the project in browser:

   ```
   http://localhost/aura-of-akeri
   ```

---

## 📂 Project Structure (Typical)

```
├── admin/              # Head Admin features
├── branch_admin/       # Branch Admin features
├── user/               # User interface & booking
├── assets/             # CSS, JS, images
├── database/           # SQL files
├── index.php           # Entry point
├── README.md           # Documentation
```

---

## 📐 System Design

* **Architecture:** Web-based client–server model
* **Design Artifacts:**

  * Use Case Diagrams
  * Class Diagram
  * ER Diagram
  * Sequence Diagram
* **Data Integrity:** Maintained through structured relational database design
* **Security Measures:**

  * Authentication & authorization
  * Basic firewall protection
  * HTTPS for data transmission
  * Input validation to prevent SQL injection

---

## 📚 Learning Outcomes

* Practical experience with **PHP & MySQL**
* Applying **Software Requirement Specification (SRS)**
* Role-based system design
* Database modeling and CRUD operations
* Team-based software development

---

## 👥 Contributors (Group – 7)

* **Nyan Pyae Maw**
* **Min Sett Paing**
* **Akeri Myint Zaw**
* **Su Myat Wai**
* **Khin Jue Zan**
* **Thaw Htet Swann**

---

## 📜 License

This project is developed for **academic and educational purposes** under the **University of Information Technology** curriculum.
All rights reserved by the contributors.



* 🔹 **Shorter README (for quick grading)**
* 🔹 **Burmese version**
* 🔹 **Add screenshots section**
* 🔹 **Convert this into CV / portfolio description**

Just tell me — this README is already **submission-ready & GitHub-ready** ✅
