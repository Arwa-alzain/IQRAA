# IQRAA Library Management System

**Implemented by:** Arwa Alzain

This project is a Library Management System called **IQRAA**, focusing on the **Books Management** and **Reports** modules for the Manager interface. It is built with **Java Swing** and connected to a relational database using **JDBC**.

---

## 📚 Books Module

The Books screen allows managers to fully manage the library’s book collection.

### Features
- **CRUD Operations**:
  - **Add** new books
  - **Update** existing books
  - **Delete** books by BookID
  - **Search** for specific books
  - **Reset** to reload all books
- **GUI Design**:
  - Multi-panel layout using `AbsoluteLayout`
  - JTable displays book details: `BookID`, `Title`, `Author`, `Genre`, `PublicationDate`, `Description`, `Availability`
  - Scrollable table using `JScrollPane`
- **Database Integration**:
  - Connected via JDBC
  - Methods to load and update book records dynamically

### Validation & Exception Handling
- Ensures numeric BookID and correct `yyyy-MM-dd` format for publication date
- Handles:
  - `SQLException` for database errors
  - `NumberFormatException` for invalid numeric input
  - `IllegalArgumentException` for invalid dates

### Testing & Verification
- Functional testing for all operations (Add, Update, Delete, Search, Reset)
- Edge cases (empty fields, invalid formats)
- Database consistency validation
- UI updates and error message handling

---

## 📊 Reports Module

The Reports screen provides real-time library statistics.

### Features
- **Library Statistics**:
  - Total books
  - Borrowed books
  - Available books
- **Popular Books**:
  - Top 3 most popular books displayed
- **Member Statistics**:
  - Total users
  - Users with late returns
  - Active users
- **GUI Design**:
  - Multi-panel layout with top, center, and bottom sections
  - Labels dynamically updated from database queries

### Exception Handling
- Database connection issues
- SQL syntax errors
- Constraint violations
- Invalid table/column references
- Concurrency issues
- Driver errors

### Verification
- Cross-checked statistics with database
- Ensured all labels reflect accurate data in real time

---

## ⚙️ Technologies Used
- Java Swing (GUI)
- JDBC (Database connectivity)
- SQL (Database queries)
- AbsoluteLayout for flexible panel design

---

## 📝 Notes
- Designed for library managers to efficiently manage books and track statistics
- Handles invalid input and database exceptions gracefully
- Tested extensively for UI consistency, database accuracy, and functional reliability

---

## 👩‍💻 Author

**Arwa Alzain**

- 📧 Email: [arwaahalzain@gmail.com](mailto:arwaahalzain@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/arwa-alzain](https://www.linkedin.com/in/arwa-alzain/)
- 🐙 GitHub: [github.com/Arwa-alzain](https://github.com/Arwa-alzain)

---

