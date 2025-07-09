# apexplanet-task4-security-crud
# Secure Blog CRUD Application (PHP & MySQL)

This project is Task 4 of the 45-day internship program at ApexPlanet Software Pvt. Ltd.  
It focuses on **security enhancements** in a blog-based CRUD application using **PHP and MySQL**.

## 🔐 Features Implemented

- ✅ Secure Login and Registration using password hashing
- ✅ Role-Based Access Control (Admin / Editor)
- ✅ Prepared Statements (to prevent SQL Injection)
- ✅ Client-side & Server-side Form Validation
- ✅ Session-based User Authentication
- ✅ CRUD (Create, Read, Update, Delete) operations on blog posts

## 👥 User Roles

- **Admin**: Can create, edit, and delete blog posts
- **Editor**: Can only create and edit blog posts

## 🛠️ Technologies Used

- PHP (Core)
- MySQL (Database)
- HTML/CSS
- JavaScript (for client-side validation)
- PDO (PHP Data Objects) for secure DB operations

## 🧪 Security Measures

- All DB queries use prepared statements
- Passwords stored using `password_hash()`
- Input fields are validated both client and server side
- Role-based access implemented to restrict certain operations


