# 📚 IQRAA Library Management System

**Team Member:** Arwa Alzain

This project is a Library Management System called **IQRAA**, focusing on managing books, reports, and library users. The following sections describe my contributions to the **Books** and **Reports** modules.

---

## 🛠️ Contribution Overview

I was responsible for the design and implementation of the **Books** and **Reports** screens of the Library Management System.

---

### 📖 Books Screen

**🖼 Layout:**  
- Main panel (`jPanel1`) using `AbsoluteLayout` with a light background.  
- Left panel (`jPanel2`) with a dark background showing rights label and IQRAA logo.  
- Labels (`jLabel3`–`jLabel9`) for **Book ID, Title, Author, Genre, Publication Date, Description, Availability**.  
- Text fields (`jTextField1`–`jTextField8`) for input with placeholder borders.  
- Buttons (`jButton2`–`jButton6`) for **Add ➕, Update ✏️, Delete 🗑️, Search 🔍, Reset 🔄**.  
- `jTable1` inside `jScrollPane` to display all books dynamically.

**💾 Database Interaction:**  
- Connected via JDBC.  
- Methods to **load, add, update, delete, and search** book records.  
- `jTable1` refreshes automatically after each operation.

**⚠️ Validation & Exception Handling:**  
- Ensures BookID is numeric and PublicationDate is in `yyyy-MM-dd` format.  
- Handles `SQLException`, `NumberFormatException`, and `IllegalArgumentException`.

**🧪 Testing:**  
- Functional testing for all CRUD operations.  
- Edge cases: empty fields, incorrect formats, invalid data types.  
- Database consistency verification.  
- UI updates correctly with clear error messages.

---

### 📊 Reports Screen

**🖼 Layout:**  
- Main panel (`jPanel1`) using `AbsoluteLayout` with light background.  
- Left panel (`jPanel2`), top header (`jPanel3`), center panel (`jPanel4`), bottom panel (`jPanel5`) with dark backgrounds.  
- Labels for **library activities, popular books, and member statistics**.  
- Navigation button to return to Manager Home Screen.

**💾 Database Interaction:**  
- Queries retrieve real-time statistics for:  
  - Total books 📚, Borrowed books 📖, Available books ✅  
  - Top 3 popular books 🌟  
  - Number of users 👥, Late return users ⏰, Active users 🟢

**⚠️ Validation & Exception Handling:**  
- Handles database connection issues, SQL syntax errors, constraint violations, invalid operations, concurrency issues, and driver errors.

**🧪 Testing:**  
- Verified all numbers match database records.  
- UI updates reflect database changes in real time.  
- Checked layout and labels for clarity.

---

## 🛠 Technologies Used

- Java Swing 🖥️  
- JDBC 🔗  
- SQL 🗄️  
- AbsoluteLayout 📐  

---

## 👩‍💻 Author

**Arwa Alzain**

- 📧 Email: [arwaahalzain@gmail.com](mailto:arwaahalzain@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/arwa-alzain](https://www.linkedin.com/in/arwa-alzain/)
- 🐙 GitHub: [github.com/Arwa-alzain](https://github.com/Arwa-alzain)

---

