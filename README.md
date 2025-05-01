# ✈️ Airline Reservation System in PHP

![Platform](https://img.shields.io/badge/Platform-Web-blue)
![Language](https://img.shields.io/badge/Language-PHP-lightgreen)
![Frontend](https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-yellowgreen)
![Database](https://img.shields.io/badge/Database-MySQL-blue)
![UX/UI](https://img.shields.io/badge/UI%2FUX-Optimized-brightgreen)

---

## 📌 Description

A **complete Airline Reservation System** built using **PHP and MySQL**, designed with separate **Admin** and **User panels**. It provides a clean, intuitive interface for users to **search flights, book tickets, make payments**, and download their **booking receipt**. The system includes **authentication, admin verification for payments**, and **ticket cancellation features**.

This project is ideal for learning **full-stack web development** using **pure PHP** without frameworks, and it integrates well with **XAMPP** for local development.

---

## 🚀 Key Features

### 🧑‍💼 User Panel

- 🔍 Search available flights by date, route, or class  
- 🛫 Book flights and make reservations  
- 💳 Make secure payment (requires admin approval)  
- 📥 Download booking ticket and payment receipt (PDF)  
- 🔁 Cancel tickets before departure  
- 🔐 Forgot password & email verification  
- 👀 View booking & flight status

### 🛠️ Admin Panel

- ➕ Add / update / delete flights  
- 👥 Manage users and their bookings  
- ✅ Verify payments manually  
- 📤 Bulk upload flights (CSV)  
- 📥 Bulk download bookings / payments (CSV)  
- 📊 Dashboard to monitor system activity  

---
📂 Learn more about the project structure and features from the detailed PowerPoint presentation:

[![Open Presentation](https://img.shields.io/badge/Open-PPT_File-orange?style=for-the-badge&logo=microsoft-powerpoint)](docs/Airline_Reservation_Presentation.pptx)
[![Download PPT](https://img.shields.io/badge/Download-Presentation-lightblue?style=for-the-badge&logo=download)](docs/Airline_Reservation_Presentation.pptx)

---

## 👨‍💻 Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP (Core PHP)  
- **Database**: MySQL (via phpMyAdmin on XAMPP)  
- **Email Verification**: PHP Mail  
- **PDF Generation**: TCPDF / Dompdf (as per your setup)  
- **File Upload/Download**: PHP CSV handling  

---

## 📲 How Users Use the App

1. 🔐 **Register/Login** from the user panel  
2. 🔍 **Search flights** by entering destination, date, and class  
3. 🛒 **Book flight** and proceed to payment  
4. 💳 **Make payment** (goes to admin for manual verification)  
5. 🧾 Once verified, download the **ticket & payment receipt**  
6. ❌ **Cancel the ticket** before departure if needed  
7. 🔐 Forgot password? Use the **"Forgot Password"** feature with email authentication  

---

## 👨‍🔧 How Developers Can Use This Project

### 🔧 Prerequisites

- XAMPP (Apache + MySQL)
- PHP 7.x or 8.x
- Git (optional)
- Web browser

### 🛠️ Installation Steps

1. 🔽 **Clone the Repository**
   ```bash
   git clone https://github.com/aayush61203/airline-reservation-system.git
   ```

2. 📁 **Move project** to your XAMPP `htdocs` folder  
   Example:
   ```
   C:\xampp\htdocs\airline-reservation-system\
   ```

3. 🛢️ **Import the Database**
   - Open `phpMyAdmin`  
   - Create a new database: `airline_system`  
   - Import the SQL file provided in `/database/airline_system.sql`

4. ⚙️ **Configure `config.php`**
   Update your database username/password:
   ```php
   $db_host = "localhost";
   $db_user = "root";
   $db_pass = "";
   $db_name = "airline_system";
   ```

5. 🌐 **Start Apache and MySQL** in XAMPP  
   Access the app:  
   ```
   http://localhost/airline-reservation-system/
   ```

---

## 🎨 UI & UX Design Principles

- Dark & Light theme switch (optional)
- Clean table layouts with alternating row colors
- Responsive layout for mobile devices
- Clear CTA buttons (Book, Pay, Cancel)
- Tooltips and validation on form fields
- Smooth navigation with minimal clicks
- Minimal popup messages & confirmation modals

---

## 📩 Contact

If you have any questions or suggestions:

📧 **Email:** [contactaayushshah@gmail.com](mailto:contactaayushshah@gmail.com)  
🌐 **GitHub:** [@aayush61203](https://github.com/aayush61203)
