
## 🍰 Pastry Shop Management System
## Live Hosted at: https://macrodmt.rf.gd
## 📌 Overview

The **Pastry Shop Management System** is a **web-based application** designed to manage the daily operations of a pastry shop efficiently. Built with **HTML, CSS, JavaScript, PHP (MVC structure)**, **AJAX**, and **MySQLi**, this system supports **role-based access** for **Admin**, **Employee**, and **Customer** users.

This project helps automate registration, login, product management, sales tracking, and customer order processing in a secure and user-friendly way.

---

## 🎯 Key Features

### 🔐 **Role-Based Registration & Login**

* Users select their role (**Admin**, **Employee**, or **Customer**) during registration.
* After account creation, users log in through a role-based login page.
* Authentication checks credentials and redirects to the respective dashboard.

### 🧑‍💼 **Admin Functions**

* View, Add, Update, Delete Admins
* Manage all products: Add, View, Update, Delete
* View Sales Reports
* Manage own profile
* Secure logout

### 👨‍🔧 **Employee Functions**

* View and update own profile
* Add, update, delete customer records
* View products
* Add new products
* View sales reports
* Secure logout

### 🧑‍🍳 **Customer Functions**

* View and update own profile
* View available products
* Add products to cart
* Place orders and make payments
* Secure logout

---

## ⚙️ **Technology Stack**

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP (MVC)
* **Database:** MySQLi
* **Asynchronous Requests:** AJAX

---

## 🗂️ **Project Structure**

```
/pastry-shop-management
├── index.php
├── /controllers
├── /models
├── /views
├── /assets (CSS, JS, images)
├── /config
├── /database
├── README.md
```

---

## 🚀 **How to Run the Project**

1️⃣ **Clone the Repository**

```bash
git clone https://github.com/yourusername/pastry-shop-management.git
```

2️⃣ **Import Database**

* Open **phpMyAdmin**
* Import the provided `.sql` file to create necessary tables.

3️⃣ **Configure Database**

* Update `config/config.php` with your MySQL credentials.

4️⃣ **Run the Project**

* Start your local server (e.g., XAMPP, WAMP, MAMP).
* Access the project in your browser:

  ```
  http://localhost/pastry-shop-management/
  ```

---

## ✅ **Testing**

* Unit and system test cases designed and executed for:

  * User registration & login
  * Admin/Employee/Customer functionalities
  * Product CRUD operations
  * Role-based redirection and access control
* Selenium IDE used for automated test cases.
* Manual test cases documented and included in `/tests`.

---

## 🔒 **Security**

* Input validation and sanitization implemented.
* Role-based access controls.
* Session management for login/logout.

---

## 📃 **License**

This project is for educational purposes and can be modified as needed.

---

## 🤝 **Developer**

- **PROTTOY SAHA**
- AIUB
- Student from CSE Department
- Contact: prottoys28@gmail.com
---

## 📌 **Note**

If you use or modify this project, please keep this README file updated to reflect any changes to features or configuration steps.

---


