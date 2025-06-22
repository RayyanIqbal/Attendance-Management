# Attendance Management System

This is a simple **Attendance Management System** developed using **PHP** and **MySQL**. It is designed to help manage attendance records for students and administrators with a basic and clean user interface.

## 🔧 Technologies Used

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** PHP
- **Database:** MySQL

## ✨ Features

- Admin login system
- Add, edit, and delete student records
- Take and manage attendance daily
- View attendance reports
- Secure session management
- Responsive user interface

## 📁 Folder Structure

```
/Attendance-Management
│
├── css/               # Custom styles
├── js/                # JavaScript files
├── includes/          # DB connection and utility scripts
├── admin/             # Admin panel
├── student/           # Student panel
├── index.php          # Login page
└── config.php         # Database configuration
```

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/RayyanIqbal/Attendance-Management.git
   cd Attendance-Management
   ```

2. **Set up the database**
   - Create a MySQL database (e.g., `attendance_system`)
   - Import the SQL file provided (`database.sql` or similar)

3. **Configure the database connection**
   - Open `config.php`
   - Set your MySQL `host`, `username`, `password`, and `database name`

4. **Start the development server**
   - Place the folder in your web server directory (e.g., `htdocs` if using XAMPP)
   - Open `http://localhost/Attendance-Management` in your browser

## 🔐 Default Admin Credentials

```
Username: admin
Password: admin123
```

> You should change these after first login for security purposes.

## 📌 Note

- This is a beginner-friendly project intended for educational purposes.
- You are free to enhance and expand it with more features like email notifications, facial recognition, etc.

---

**Developed by [Rayyan Iqbal](https://github.com/RayyanIqbal)**
