# 💳 Bank Management System

A console-based C++ program that simulates a simplified bank management system. Designed as the final project for **CSE126 – Programming (1)** at Alexandria University, this system allows employees to manage customer accounts, perform transactions, and generate reports using a menu-driven interface.

---

## 🛠️ Features

- **Secure Login System**
  - Validates user credentials from `users.txt`.

- **Account Management**
  - Load data from `accounts.txt`
  - Add new accounts
  - Delete existing accounts (with conditions)
  - Modify account details (name, mobile, email)
  - Save changes or discard

- **Transaction Capabilities**
  - Withdraw and deposit funds (limit: $10,000)
  - Transfer money between accounts
  - Log transaction history in individual account files

- **Search Functions**
  - Search by account number
  - Advanced keyword-based search by name

- **Reporting**
  - View last 5 transactions of an account
  - Display all accounts sorted by:
    - Name
    - Balance
    - Date opened

- **Validation and Error Handling**
  - Account number format (10 digits)
  - Email format validation
  - Duplicate detection
  - Input sanitization to prevent crashes

---

## 📁 File Structure

```
.
├── main.cpp                 # Entry point of the program
├── accounts.txt            # Stores account data
├── users.txt               # Stores username and password pairs
├── <accnumber>.txt         # Individual transaction history per account
├── README.md               # Project documentation
└── report.pdf              # Project report and user manual
```

---

## 🧪 Sample Data Format

### `users.txt`
```
ahmed.mohamed 123$@1
ali.ahmed 654321
ziad.ali 123abc
```

### `accounts.txt`
```
9780136019,Mohamed Ali,m.ali@gmail.com,10000.54,01254698321,12-2008
9780135102,Omar Ahmed,omar@outlook.com,40000.73,01122553164,12-2015
```

---

## 🧭 Navigation & Menu

- Initial options: `LOGIN` / `QUIT`
- Post-login options:
  - ADD, DELETE, MODIFY
  - SEARCH, ADVANCED SEARCH
  - WITHDRAW, DEPOSIT, TRANSFER
  - REPORT, PRINT (with sorting), SAVE, QUIT

---

## 🧾 Deliverables

- ✅ Source Code
- ✅ Final Report
- ✅ Sample Runs & User Manual
- ✅ Algorithms (search, sort)


---

## 🛡️ Notes & Guidelines

- Each function is modular and well-documented
- Data validation is enforced throughout the program
- Error messages help guide user input
- History is maintained for each transaction
- Cheating policy strictly enforced – all code is original

---
