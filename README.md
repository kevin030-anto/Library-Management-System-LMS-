# 📚 Library Management System (LMS)

A Library Management System built with **PHP**, **SQL**, **HTML**, and **JavaScript**, designed to run locally using **WampServer2.1e-x32**. This project allows easy and efficient management of Books, Newspapers, Magazines, and Members in a library setting.

---

## 🚀 Features

- 🔍 **Add, Edit, Delete, and Manage:**
  - Books
  - Newspapers
  - Magazines
  - Library Members

- 📦 **Track Borrowed Items:**
  - Monitor whether books, newspapers, or magazines have been returned or are still checked out

- 💸 **Automatic Fine Calculation:**
  - Automatically calculates and tracks fines for overdue returns

---

## 🖼️ Sample Project Screenshot
![Project Screenshot](https://github.com/kevin030-anto/LMS/blob/main/Image/Home%20Page.png)

---

## 🛠️ Technologies Used

- **PHP** – Server-side scripting
- **SQL** – Database management
- **HTML/CSS** – Front-end structure and styling
- **JavaScript** – Front-end interactivity
- **WampServer2.1e-x32** – Local development server environment

---

## 🖥️ Installation & Setup (Local)

1. **Download & Install [WampServer2.1e-x32](http://www.wampserver.com/en/)**  
   Make sure WampServer is installed and running on your local machine.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/library-management-system.git

3. **Move Project to WAMP Directory: Copy the project folder to:**
   ```bash
   C:\wamp\www\Library Management PHP\Library Management PHP\LMS

4. **Create the Database:**
   - Open phpMyAdmin via http://localhost/phpmyadmin
   - Create a new database (e.g. library_db)
   - Import the SQL file included in the project (e.g. database.sql)
   - Example Screenshots in (../LMS/Image/)
  
  5. **Configure Database Connection: (Optional)**
     - Open the config file (e.g. config.php)
     - Update database credentials:
       ```bash
       $host = "localhost";
       $user = "root";
       $pass = "";
       $db   = "library_db";

  6. **Run the Project: Navigate to:**
     - http://localhost/Library%20Management%20PHP/Library%20Management%20PHP/LMS
    
  7. **👥 User Roles (Optional for Future Enhancements):**
     - Admin: Full access to all features
     - Librarian: Manage books and members
     - Member: View and track their borrowed items
     
  8. **📌 Future Improvements:**
     - Member login & tracking system
     - Email reminders for due dates
     - Advanced search & filter
     - Responsive mobile-friendly design
     
  9. **📝 License:**
      - This project is open-source and available under the MIT License.
    
  ---

## 💡 Author

GitHub: [@kevin030-anto](https://github.com/kevin030-anto)

---
