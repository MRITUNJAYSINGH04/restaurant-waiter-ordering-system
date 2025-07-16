Online Restaurant Waiter Ordering System with Mobile App
A complete online food ordering system built using PHP & MySQL, paired with a native Android mobile app for waiters to take and manage orders directly from their smartphones or tablets.

✅ Powerful. 📱 Mobile-integrated. 🍴 Table-centric.

🔧 Project Overview
This project allows restaurants to digitize their order management process. The system handles table-by-table food ordering, real-time kitchen notifications, feedback collection, bill generation, and more. The admin panel provides full control over menu items, table status, taxes, discounts, and role-based access (waiter, kitchen manager, etc.).

📲 Features
Web Admin Panel (PHP & MySQL):
Role-wise login: Admin, Super Admin, Waiter, Kitchen Manager, Account Manager

Manage food items, images, and categories

CSV import/export for menu and orders

Table activity status: Active / Inactive

Order management by table

Tax, currency, discount settings

Customer feedback with ratings

Secure coding: SQL Injection & CSRF protection

Easily reskinnable UI

Android App (Built with Android Studio):
Waiter-focused interface to place and manage orders

Table assignment and updates

Photo support for menu items

Server connection via DataManager.java

🛠️ Installation Instructions
🖥️ Server (Web Panel):
Extract project files.

Move project folder to xampp/htdocs/

Create a database restaurant via http://localhost/phpmyadmin/

Import restaurant.sql from /db/ folder.

Run project via http://localhost/FortinRestaurant

📱 Android App:
Open FortinRestaurant > ANDROID_APP_CODE > Restaurant > in Android Studio.

Edit DataManager.java to set your local/server URL.

Build & run on device/emulator.

⚙️ System Requirements
Server:
PHP ≥ 7.0.0

OpenSSL, PDO, Mbstring, Tokenizer PHP extensions

XAMPP / WAMP / MAMP / LAMP

Mobile:
Android Studio

Internet permission

Min SDK: 21+

🧱 Folder Structure
bash
Copy
Edit
├── core/
│   ├── app/ (Models, Controllers)
│   ├── routes/web.php (Routes)
│   └── resources/views/ (HTML Templates)
├── assets/ (CSS, JS, images)
├── db/restaurant.sql
🧑‍💻 How to Edit Code
HTML: Modify inside core/resources/views/

PHP Logic: Check core/app/Http/Controllers/

Routes: Edit core/routes/web.php

App Config: Update DataManager.java and db.php

🔐 Login Credentials
Admin Panel:

Username: admin

Password: admin@123

