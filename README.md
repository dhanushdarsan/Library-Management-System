# 📚 Library Management System (Python + MySQL)

## 🧩 Description

The **Library Management System** is a Python-based software application designed to manage and automate a library’s daily operations. It efficiently handles book records, user details, and borrowing transactions using **MySQL database connectivity**.
This project demonstrates the use of Python for database-driven applications and provides an easy-to-use interface for both **Admins** and **Users**.

---

## 🚀 Key Features

### 📖 Book Management

* Add, update, or delete books with details such as **Title, Author, ISBN, Genre, and Quantity**.
* View available and borrowed books in real-time.

### 👥 Borrower Management

* Add and manage borrower details including **Name, Contact Info, and Membership ID**.
* Edit or remove borrower profiles when necessary.

### 🔄 Book Borrowing & Returning

* Borrow books by linking borrower IDs to book details.
* Track due dates and manage overdue books automatically.
* Update database upon return and calculate fines if applicable.

### 🔍 Book Search & Availability

* Search books by **Title, Author, or Genre**.
* Display **real-time availability** of books.

### 💰 Fine Calculation

* Auto-calculate late return fines based on predefined rules.
* Update and record fines for each transaction.

### 🔐 Authentication & Validation

* Admin and User login system.
* Input validation to maintain data integrity.

### 📊 Reporting

* Generate reports on borrowed books, active users, and collected fines.

---

## 🛠️ Technologies Used

* **Python 3.x** – Core application logic
* **MySQL** – Database management
* **MySQL Connector for Python** – Database connectivity
* **PyCharm / VS Code** – Recommended IDE

---

## ⚙️ Installation & Setup

1. **Clone this repository:**

   ```bash
   git clone https://github.com/<your-username>/Library-Management-System.git
   cd Library-Management-System
   ```

2. **Install dependencies:**

   ```bash
   pip install mysql-connector-python
   ```

3. **Set up the MySQL Database:**

   * Create a new database (e.g., `library_db`)
   * Import the provided `.sql` file (if available)
   * Update your database credentials in the main Python file

4. **Run the Application:**

   ```bash
   python main.py
   ```

---

## 🧑‍💻 Project Structure

```
Library-Management-System/
│
├── main.py                  # Entry point for the program
├── Operations.py            # Core functionality and database operations
├── AdminMenu.py             # Admin functionalities
├── User.py                  # User functionalities
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

## ⭐ Acknowledgment

This project was developed for educational purposes to strengthen skills in **Python programming, database management, and software design.**

---

Would you like me to make it more **modern GitHub style** — with badges (like Python version, MySQL used, etc.) and emoji icons — so it looks even better when displayed on your GitHub profile?
