# 🌿 GreenGraph
**Project Type:** Project Allocation System  

GreenGraph is a web-based Project Allocation System that automates fair project distribution using academic metrics, reducing manual effort and improving transparency in academic project management.

---

## ✨ Features

- Automated project allocation based on academic criteria
- Role-based authentication (Admin, Student, Faculty)
- Student group creation and project preference selection
- Secure login, logout, and password recovery
- Admin-controlled allocation workflow
- Clean and user-friendly interface

---

## 🛠️ Tech Stack

- **Backend:** PHP  
- **Database:** MySQL  
- **Frontend:** HTML, CSS, JavaScript  
- **Database Management:** phpMyAdmin  

---

## 🗄️ Database

- SQL file for database import is available in:
- A detailed PDF explaining the database schema and tables is provided in the same directory.

---

## 👨‍💼 Admin Module

### Allocation Control
- Manages the complete project allocation process.
- Allocation is performed using the **average CPI of group members**.
- `flush.php` is used for master reset of the database.

### Admin Capabilities
- Manage students, faculty, and projects
- Add, update, delete, enable, or disable records
- Reset user passwords
- Monitor allocation status

---

## 🎓 Student Module

- Login via the main home page (`index.php`)
- Create and manage student groups
- Select and prioritize project preferences
- View allocated projects
- Secure logout functionality

---

## 🔐 Authentication & Security

### Login System
- Separate login systems for Admin and Students

### Change & Forgot Password
Password-related features are handled inside the `change_pass` folder:
- Forgot password workflow
- Change password functionality
- CAPTCHA generation
- JavaScript-based input validation

---

## 👩‍🏫 Faculty & Project Management

- Admin-only access to manage:
- Faculty
- Students
- Projects
- GUI-based management through:
- `faculty.php`
- `student.php`
- `project.php`

> Faculty management is restricted to Admin access only.

---

## 📁 F / S / P Modules

Dedicated folders for **Faculty (F)**, **Student (S)**, and **Project (P)** management:
- Add, update, and delete records
- Enable or disable entries
- Admin-controlled password changes
- Input validation using JavaScript

---

## ℹ️ About Page

- `about_us.php` displays project and author information.

---

## 👨‍💻 Author

**Yuvraj Kumar Jaiswal**  
*Technical Software Engineer*

---









