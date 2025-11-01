# 🏦 Bank Management System in C

A console-based application simulating core banking operations using C programming and file handling. This project demonstrates structured data management, user interaction via terminal, and persistent storage using text files.

## 📌 Overview

This Bank Management System allows users to perform essential banking tasks such as creating accounts, depositing and withdrawing money, and viewing account details. It’s designed as a menu-driven program for clarity and ease of use.

## ✨ Features

- 🧾 Create new customer accounts
- 🔍 Search accounts by ID or name
- 💰 Deposit and withdraw funds
- 📝 Update account information
- ❌ Delete customer accounts
- 📂 Persistent data storage using file I/O
- 🖥️ Terminal-based user interface

## 🛠️ Technologies Used

- **Language:** C (GCC)
- **Libraries:** `stdio.h`, `stdlib.h`, `string.h`, `unistd.h`
- **Concepts:** File I/O, string manipulation, loops, conditionals, system calls

## 🚀 Getting Started

### Prerequisites

- GCC compiler (Linux, macOS, or Windows with MinGW)
- Terminal or command prompt

### Compilation

```bash
gcc bank_management.c -o bank

### run
./bank
./transaction
./a


bank-management-system/
├── bank_management.c       # Main source code
├── accounts.txt            # Data file (auto-generated)
├── README.md               # Project documentation
└── .gitignore              # Git ignore rules
