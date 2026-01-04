🌿 GreenGraph

Project Type: Project Allocation System

GreenGraph is a web-based Project Allocation System designed to automate and optimize the allocation of academic projects to student groups. The system ensures a fair, structured, and transparent allocation process using defined academic criteria, reducing manual effort and administrative overhead.

✨ Key Features

Secure Admin, Student, and Faculty authentication

Automated project allocation based on group average CPI

Student group creation and project preference selection

Admin-controlled allocation workflow

Password recovery with CAPTCHA validation

Role-based access control

Clean and functional user interface

🛠️ Tech Stack

Backend: PHP

Database: MySQL

Frontend: HTML, CSS, JavaScript

Database Management: phpMyAdmin

🗄️ Database

The SQL file required for database import is available inside:
images/database/

A detailed PDF explaining the database schema and tables is provided in the same directory.

👨‍💼 Admin Module
🔹 Allocation Control

Admin manages the complete project allocation process.

Allocation logic is based on the average CPI of group members, ensuring fairness.

flush.php is used for master reset of the database.

🔹 Admin Capabilities

Manage students, faculty, and projects

Enable / disable records

Update and delete data

Reset user passwords

View allocation status

🎓 Student Module

Login from the main home page (index.php)

Create and manage student groups

Select and prioritize project preferences

View allocation results

Secure logout functionality

🔐 Authentication & Security
Login System

Separate login systems for Admin and Students

Admin login/logout handled independently

Change & Forgot Password

All password-related functionality is managed inside the change_pass folder:

Forgot password workflow

Password change functionality

CAPTCHA generation

JavaScript-based input validation

👩‍🏫 Faculty & Project Management

Admin-only access for:

Faculty management

Student management

Project management

Files:

faculty.php

student.php

project.php

GUI-based interfaces for easy data handling

⚠️ Faculty-related operations are restricted to admin access only.
Other general features can be accessed by faculty as permitted.

📁 F / S / P Modules

Dedicated folders for Faculty (F), Student (S), and Project (P) management:

Add, update, delete records

Enable / disable entries

Change passwords via admin

JavaScript validation for inputs

ℹ️ About Page

about_us.php displays information about the project and its creator.

🚀 Purpose of the Project

GreenGraph was developed to:

Eliminate manual project allocation errors

Ensure fairness using academic metrics

Simplify coordination between students, faculty, and administrators

Provide a scalable solution for academic institutions

👨‍💻 Author

Yuvraj Kumar Jaiswal
Software Engineer
