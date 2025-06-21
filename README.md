
# 🍰 Pastry Shop Management System

A web-based application designed to manage the operations of a pastry shop efficiently. The system supports role-based access for Admins, Employees, and Customers. 
It was developed using the **MVC (Model-View-Controller)** architectural pattern to ensure modularity, scalability, and maintainability.

## Live Hosted at: https://macrodmt.rf.gd

## 🧰 Tech Stack

- **Frontend:** HTML, CSS, JavaScript, AJAX
- **Backend:** PHP (Structured in MVC)
- **Database:** MySQLi
- **Web Server:** Apache (XAMPP recommended)

## 📌 Key Features

### 🔐 Authentication
- Role-based registration & login system (Admin, Employee, Customer)
- Input validation & session management

### 👤 Admin Features
- Manage profile
- Add/View/Update/Delete Admins
- Add/View/Update/Delete Products
- View overall sales reports

### 👨‍💼 Employee Features
- Manage profile
- Add/Update/Delete Customers
- View/Add Products
- View sales records

### 🛍️ Customer Features
- Manage personal profile
- Browse products
- Add items to cart and place orders
- Simulated payment option

## 📁 Project Structure (MVC)

```

/controllers     → Handles business logic
/models          → Handles database interactions (CRUD with MySQLi)
/views           → UI pages rendered to the browser
/assets          → Static files (CSS, JS, Images)
/config          → Database connection & configuration files
/index.php       → Front controller for request routing

```

## 🗃️ Database

- Database used: **MySQLi**
- Ensure database setup by importing the all available SQL file as '.sql' provided in the project folder.

## 🚀 Setup Instructions

1. Clone or download the project to your local machine.
2. Place the project folder in your server root directory (e.g., `htdocs` in XAMPP).
3. Import the `database.sql` file into your MySQL server using phpMyAdmin or command line.
4. Configure your database credentials in `/config/db.php`.
5. Start Apache and MySQL using XAMPP or your local server.
6. Open the project in your browser via `http://localhost/pastry-shop`.

## 📄 License

This project is developed for educational and learning purposes.

---

## 👨‍💻 Author

- **PROTTOY SAHA**
- AIUB
- Student from CSE Department
- Contact: prottoys28@gmail.com
---




