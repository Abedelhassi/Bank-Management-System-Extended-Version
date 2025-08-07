# 🏦 Bank Management System – Extended Version

This is an enhanced version of the Bank Client Management System created using C++, developed as part of my programming practice and learning journey from the ProgrammingAdvices.com roadmap.

> 🔁 This project builds on the original bank system and introduces transactions, deposit/withdraw logic, total balance tracking, and better file management using fstream.

---

## 🔧 Features

- Show all clients and their balances
- Add new clients with validation
- Update or delete existing clients
- Search for a client by account number
- Perform transactions:
  - Deposit money
  - Withdraw money
  - View total balance across all clients
- Store data persistently in Clients.txt using a custom serialization format
- Menu-driven user interface
- Code organized with:
  - struct for client data
  - vector for in-memory record storage
  - Custom file reading and writing logic
  - Modular functions for operations

---

## 🧱 Data Structure

`cpp
struct sClient {
    string AccountNumber;
    string PinCode;
    string Name;
    string Phone;
    double AccountBalance;
    bool MarkForDelete = false;
};

Saved in Clients.txt in this format:

AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance


---

🧩 Menus

🔹 Main Menu

[1] Show Client List
[2] Add New Client
[3] Delete Client
[4] Update Client Info
[5] Find Client
[6] Transactions
[7] Exit

🔹 Transactions Menu

[1] Deposit
[2] Withdraw
[3] Show Total Balances
[4] Return to Main Menu


---

🧠 What I Learned

Decomposing a large problem into manageable modules

Handling file I/O and custom data storage

Building a transaction system with basic validation

Using enums, structs, and procedural programming principles

Managing multiple features inside a single C++ program



---

📁 Project Structure

Bank-Management-System-Extended/
│
├── main.cpp          → Full source code
├── Clients.txt       → Database file for client records
└── README.md         → Project documentation


---

▶️ How to Run

1. Clone the repo or download the files.


2. Open main.cpp in Visual Studio or any C++ IDE.


3. Build and run the project.


4. The system will display the main menu in the console.




---

📚 Resources

Course: 07 - Algorithms and Problem Solving Level 3

Instructor: Mohammed Abu-Hadhoud

Website: ProgrammingAdvices.com

YouTube Channel: Programming Advices



---

👨‍💻 Author

Abed-El-Hassib Lakhdari
Student in Computer Science | Passionate about Problem Solving & Software Engineering
