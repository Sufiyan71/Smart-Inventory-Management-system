# Inventory Management System (PHP & MySQL)

## Overview

The **Inventory Management System** is a web-based application built using **PHP, MySQL, JavaScript, and Bootstrap** to efficiently manage inventory, track stock levels, and generate reports. It allows businesses to streamline their inventory tracking, reduce errors, and optimize stock control.

## Features

- **User Authentication**: Secure login and user role management with Admin, Special User, and Employee roles.
- **Admin Panel**: Full control over the system, including user management and inventory tracking.
- **Special User Panel**: Access to product and media management.
- **Employee Panel**: Sales record management and report viewing.
- **Product Management**: Add, edit, and delete products.
- **Category Management**: Organize products into categories.
- **Stock Management**: Update stock levels and track inventory movements.
- **Sales & Purchase Tracking**: Log sales and purchases with timestamps.
- **Reporting**: Generate detailed sales reports (daily, weekly, and monthly).
- **Media Management**: Upload and attach images to products.
- **Responsive Design**: Fully responsive UI using Bootstrap for an enhanced user experience.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP (Core PHP, MySQLi for database interaction)
- **Database**: MySQL
- **Libraries**: DataTables, Chart.js for analytics

## Installation Guide

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sufiyan71/Smart-Inventory-Management.git
   ```
2. **Setup Database**
   - Create a database in MySQL.
   - Import the provided `DATABASE FILE/inventory.sql` into your database using phpMyAdmin.
3. **Configure Database Connection**
   - Open `config.php`.
   - Update database credentials:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "inventory_db";
     ```
4. **Start the Server**
   - Use XAMPP, WAMP, or MAMP to run Apache and MySQL.
   - Place the project folder in the `htdocs` directory (for XAMPP users).
   - Access the system at `http://localhost/[ENTER_PROJECT_FOLDER_NAME_HERE]`

## Usage

1. **Login**: Use the default admin credentials (provided in `01 LOGIN DETAILS & PROJECT INFO.txt`).
2. **Manage Inventory**: Add categories, products, and stock levels.
3. **Track Transactions**: Log purchases and sales.
4. **Generate Reports**: View inventory reports with analytics.
5. **Media Management**: Upload product images for better organization.

## System Requirements

- PHP version **5.6.3** (or compatible)
- MySQL database
- Apache server (XAMPP, WAMP, or MAMP recommended)
- Web browser (Google Chrome, Mozilla Firefox recommended)

## Future Enhancements

- Barcode scanner integration.
- Role-based access control (RBAC) improvements.
- Automated email notifications for low stock.
- Multi-language support.
- Advanced analytics dashboard.

## License

This project is licensed under the **MIT License**.


