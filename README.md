# 📁 Project Management System

A full-stack web-based Project Management System designed for efficient task handling, team collaboration, and project tracking. Built using **React.js**, **Java (JSP/Servlets)**, and **MySQL**, deployed on **GlassFish Server**.

---

## 📄 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Requirements](#system-requirements)
- [Installation & Setup](#installation--setup)
- [How to Run](#how-to-run)
- [Folder Structure](#folder-structure)
- [Contributors](#contributors)
- [License](#license)

---

## 📌 Overview

This system provides role-based access for:
- 🛠️ **Admin** – User & project oversight  
- 📂 **Project Manager** – Project and task assignment  
- 👨‍💻 **Team Member** – Task updates and collaboration  

The system helps streamline project workflows, track task status, manage deadlines, share files, and organize team activities through an intuitive dashboard.

---

## ✨ Features
- Secure role-based login and authentication
- Project and task creation with deadline tracking
- Assignment of tasks to team members
- Event creation and scheduling
- File uploads per project
- Comment system for communication
- Admin analytics dashboard
- MySQL-based data storage with ER-modeled schema

---

## 🛠 Technologies Used

**Frontend**:
- HTML, CSS, JavaScript
- Bootstrap / Material UI

**Backend**:
- Java (Servlets)
- MySQL Database
- JDBC for DB interaction

**Server**:
- GlassFish Server 6.0.1

**Other Tools**:
- GitHub (Version Control)
- NetBeans IDE
- phpMyAdmin (for DB management)

---

## 💻 System Requirements

| Component       | Minimum Requirement         |
|----------------|-----------------------------|
| OS             | Windows 11 / Linux          |
| RAM            | 4 GB (8 GB Recommended)     |
| Java           | JDK 11+                     |
| MySQL          | v5.7 or newer               |
| Server         | GlassFish Server v6.0.1     |
| IDE            | NetBeans (preferred)        |
| Browser        | Chrome / Firefox            |

---

## 🚀 Installation & Setup

### 1. Clone the Repository

git clone https://github.com/Navin049/FSEP.git


### 2. Import the Project into NetBeans

Open NetBeans IDE
Choose Open Project and select the cloned folder

### 3. Set Up MySQL Database
Create a new MySQL database: project_db

Import the provided SQL file from /db/project_db.sql using phpMyAdmin or MySQL CLI

### 4. Configure Database Connection
In DBConnection.java, update:'

String url = "jdbc:mysql://localhost:3306/project_db";
String username = "root";
String password = "your_password";


### 5. Deploy to GlassFish Server
Add your project to GlassFish server in NetBeans

Clean and Build the project

Right-click → Run

How to Run
Start GlassFish Server in NetBeans

Access the app at:

Copy code
http://localhost:8080/ProjectManagementSystem/
