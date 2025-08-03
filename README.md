# 🌐 Documentation

## 📖 Overview
This is a role-based web application built using PHP and MySQL. It supports multi-level access control including Superadmin, Admin, Moderator, and User roles. Each role has specific functionalities tailored to its permissions.

---

## ✨ Features
- Secure authentication and role-based access control
- Modular MVC architecture
- Upload and manage images
- Logging system for error tracking
- Bootstrap-based responsive UI

---

## 👥 Access Roles

### 🔑 Superadmin Functionality
- Manage all user roles (Admin, Moderator, User)
- View complete system logs
- Access all data and settings

### 🛠️ Admin Functionality
- Create and manage moderators
- Manage user data and content
- Access system-wide configurations

### 🧰 Moderator Functionality
- Monitor user activity
- Moderate content
- Generate reports

### 👤 User Functionality
- Register/login/logout
- View and manage own profile
- Upload and manage files

---

## ⚙️ Requirements
To run this website locally, ensure you have:

- PHP `8.2.12` or higher
- XAMPP (includes Apache and MySQL)
- Any IDE that supports PHP (e.g., VSCode)
- Internet connection for loading external libraries (e.g., Bootstrap, jQuery)

---

## 🧪 Setup

1. Clone the repository.
2. Move the project to the `htdocs` folder inside XAMPP directory.
3. Import the `.sql` file from the `/sql` directory into phpMyAdmin.
4. Start Apache and MySQL via XAMPP.
5. Configure database connection inside `/config` directory (e.g., `config.php`).

---

## 📁 Directory Structure

```
/assets         # CSS, JS, images
/config         # DB and system configuration files
/controllers    # Handles business logic
/excel          # Test Excel files
/includes       # Reusable UI components (e.g., header.php, footer.php)
/logs           # Error and system logs
/models         # Data models and database abstraction
/sql            # SQL schema file(s)
/src            # Environment files
/upload         # User-uploaded images
/views          # HTML templates and views
```

---

## 🧰 Technologies Used

### Frontend:
- HTML, CSS, JavaScript
- [Bootstrap v5.3.3](https://getbootstrap.com/)
- jQuery

### Backend:
- PHP
- MySQL

---

## 📝 Notes
- Ensure write permission for `/upload` and `/logs` directories.
- Environment variables (e.g., DB credentials) should be stored in `/src`.
- Logs help track system errors and debugging.
