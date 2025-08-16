"# Banking_Management_System" 

# 🏦 Banking Management System (Java + MySQL)

The **Banking Management System** is a Core Java project integrated with **MySQL (via JDBC)** to simulate basic banking operations.  
It allows account creation, deposit, withdrawal, and balance inquiry, while ensuring secure transaction management and real-time database interaction.  
This project demonstrates the practical application of **OOP concepts**, **SQL operations**, and **Java Database Connectivity (JDBC)**.

---

## 🚀 Features
- Create new customer accounts with unique account IDs.
- Deposit and withdraw money securely.
- Balance inquiry with real-time validation.
- Secure data storage using MySQL.
- Exception handling for invalid inputs and transactions.
- Modular code design, easy to extend with new features.

---

## 🛠️ Tech Stack
- **Language:** Core Java  
- **Database:** MySQL  
- **Connectivity:** JDBC API  
- **Tools/IDE:** IntelliJ IDEA / Eclipse, MySQL Workbench  

---

## 📂 Project Structure
BankingManagementSystem/
├── src/
│ ├── Account.java
│ ├── BankingSystem.java
│ ├── DatabaseConnection.java
│ └── Main.java
├── database/
│ └── banking_db.sql
└── README.md


---

## ⚙️ Setup & Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/BankingManagementSystem.git

2.**Create the database in MySQL**

CREATE DATABASE banking_db;
USE banking_db;

CREATE TABLE accounts (
    account_id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    balance DOUBLE
);


3.**Configure Database Connection**

Open DatabaseConnection.java.

Update username, password, and database URL as per your MySQL setup.

4.**Run the project**

Compile and run Main.java from your IDE or terminal.

5.**▶️ Usage**

Create Account → Add a new customer with initial balance.

Deposit → Enter account ID and amount to deposit.

Withdraw → Enter account ID and amount to withdraw (checks balance).

Check Balance → Displays current balance of the account.

6.**📌 Future Enhancements**

Add fund transfer between accounts.

Implement account statements and transaction logs.

Upgrade to a GUI-based interface (Swing/JavaFX).

Deploy on cross-platform environments.

**📖 Learning Outcomes**

Practical implementation of OOP principles in Java.

Hands-on experience with JDBC and SQL CRUD operations.

Understanding database-driven applications.

Improved logical reasoning and problem-solving through modular system design.

**👨‍💻 Author**

Muhammed Anas
B.E. Artificial Intelligence & Machine Learning
