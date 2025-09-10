<h1 align="center">🏦 Banking System in C++</h1> <h3 align="center">💻 A Console-Based Banking Project | Users & Managers | File-Based Storage</h3>
🚀 Project Overview

This project is a console-based banking system built in C++, designed to simulate essential banking operations.
It supports both Users (customers) and Managers (administrators), allowing account creation, login, transactions, and balance management.

Data is stored in text files (users.txt, managers.txt) to ensure persistence across program runs.

🎯 Features
👤 User Operations

Create a new account

Login with credentials

Deposit & Withdraw money

View account summary (balance + transactions)

Close an account permanently

Logout

👨‍💼 Manager Operations

Login as manager (with admin credentials)

View all users with their account details

Edit or update any user’s account balance

Logout

📂 Project Files

bank.cpp → Main program source code

users.txt → Stores user data (username, password, balance)

managers.txt → Stores manager credentials (username, password)

⚙️ Setup & Run
1️⃣ Compile the Program

Open a terminal in the project directory and run:

g++ bank.cpp -o bank

2️⃣ Run the Program
./bank   # Linux / Mac
bank.exe # Windows

📌 Usage Guide
🔹 User Menu

Create Account → Enter username & password

Login → Access account options:

Withdraw funds

Deposit money

View account summary

Close account

Logout

🔹 Manager Menu

Login as Manager → Enter admin credentials

Choose operations:

View all users & balances

Edit any user’s balance

Logout

🧠 Purpose of the Project

Practice File Handling in C++ (persistent storage).

Apply OOP Concepts (classes: Database, BankAccount, Transaction, BankManager).

Build a real-world simulation of banking operations.

Strengthen problem-solving & logical thinking with C++.

🛠️ Tech Stack
Languages & Concepts	Tools & Methods
C++ (OOP, STL)	File Handling (I/O)
Classes & Objects	CRUD Operations
Data Persistence	Console-Based Interface
📫 Contact

📧 Email: ammadudin23@gmail.com
💼 LinkedIn: Muhammad Ammad-ud-Din Khan
