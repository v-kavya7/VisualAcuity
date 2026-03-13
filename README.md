👁️ VisualAcuity
A Web-Based Visual Acuity Testing System

VisualAcuity is a web-based eye vision testing application designed to simulate basic visual acuity tests through an interactive interface.

The system allows users to register, login, and perform visual tests that help evaluate eyesight clarity. This project demonstrates a full-stack web application using PHP, HTML, CSS, and MySQL.

📌 Overview

Visual acuity refers to the sharpness or clarity of vision. It is commonly measured using standardized charts where users identify letters or symbols at a specific distance.

This project provides a digital implementation of such testing systems, allowing users to experience a simplified online vision test.

✨ Features

🔐 User Authentication

User registration

Secure login/logout system

Session management

👁️ Vision Testing

Multiple visual acuity test levels

Interactive test pages

Simple test interface

🛠️ Admin Panel

Admin login access

Manage system users

🎨 Clean UI

Responsive design

Custom CSS styling

Easy navigation
User
 │
 ▼
Login / Register System
 │
 ▼
Authentication (PHP Sessions)
 │
 ▼
User Dashboard
 │
 ▼
Visual Acuity Test Pages
 │
 ▼
Results & System Management

🧱 Project Architecture

VisualAcuity
│
└── epicsGit
    │
    ├── admin.php
    ├── config.php
    ├── login.php
    ├── logout.php
    ├── register.php
    ├── user.html
    ├── s5.html
    ├── s20.html
    └── style.css
    
🛠️ Technologies Used
Frontend

HTML5

CSS3

Backend

PHP

Database

MySQL

Server

Apache (XAMPP / WAMP / LAMP)
⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/v-kavya7/VisualAcuity.git
2️⃣ Move project to server directory

Example for XAMPP:

xampp/htdocs/
3️⃣ Open project folder
VisualAcuity/epicsGit
🗄️ Database Setup

Open phpMyAdmin

Create a database

visualacuity_db

Update database configuration in config.php

$servername = "localhost";
$username = "root";
$password = "";
$dbname = "visualacuity_db";

▶️ Running the Application

Start Apache and MySQL in XAMPP.

Open browser:

http://localhost/VisualAcuity/epicsGit/login.php
📸 Screenshots

(Add screenshots here for better GitHub presentation)

Example:

Login Page
User Dashboard
Visual Test Page
Admin Panel

🚀 Future Improvements

Add Snellen eye chart simulation

Store user test results

Improve UI/UX design

Add mobile responsiveness

Implement AI-based vision analysis

Add data analytics dashboard

🤝 Contributing

Contributions are welcome!

Steps to contribute:

Fork the repository

Create a new branch

Commit your changes

Push to your branch

Open a Pull Request
