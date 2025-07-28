# Blood Bank & Donor Management System (BBDMS)

This is a **Blood Bank & Donor Management System** built using **PHP & MySQL**, originally developed by [PHPGurukul](https://phpgurukul.com). It is a web-based platform designed to manage blood donations, donors, and requests in a streamlined and organized way.

---

## 📌 Features

- Donor registration and management
- Blood stock tracking by blood group
- Request handling and approval
- Admin and user login panels
- Notification and contact modules
- Fully responsive frontend

---

## 🛠️ Technologies Used

- PHP (Core PHP)
- MySQL (Database)
- HTML5, CSS3, Bootstrap
- JavaScript / jQuery

---

## 💻 Installation Instructions (Localhost)

### Requirements
- XAMPP/WAMP/LAMP or any PHP + MySQL stack
- PHP version 7.x or 8.x

### Steps

1. Clone or download this repository:
   ```bash
   git clone https://github.com/otri927/blood-bank-donor-management-system.git
Move the folder to your XAMPP htdocs directory:

makefile

C:\xampp\htdocs\blood-bank-donor-management-system
Import the database:

Open phpMyAdmin (http://localhost/phpmyadmin)

Create a new database: bbdmsdb

Import the bbdmsdb.sql file from the project root

Configure Database Connection:

Open includes/config.php

Set your database username/password:

php

$dbh = new PDO("mysql:host=localhost;dbname=bbdmsdb", "root", "");
Run the application:

perl

http://localhost/blood-bank-donor-management-system


🧾 Credits
This project is originally created by PHPGurukul.

Original Project Page

Licensed under PHPGurukul’s distribution terms.

This version is maintained for educational and learning purposes.

✍️ Author
GitHub: @otri927

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
