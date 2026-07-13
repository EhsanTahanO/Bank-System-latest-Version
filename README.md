# Bank System (C++ Console Application)

A training project built in **C++** to simulate a simple banking system using a console interface and file-based storage.

## ✨ Features

- **Client Management**
  - Add new client
  - Update client information
  - Delete client
  - Find client
  - List all clients
  - View total balances

- **Transactions**
  - Deposit
  - Withdraw
  - Transfer between clients
  - Transfer history log

- **User Management**
  - Login system
  - Add / update / delete / find users
  - Users list
  - Login register history

## 🧱 Project Structure

```text
Bank-System-latest-Version/
├─ README.md
└─ BankSystem2/
   ├─ BankSystem2.cpp
   ├─ clsMainScreen.h
   ├─ clsLoginScreen.h
   ├─ clsBankClient.h
   ├─ clsUser.h
   ├─ clsTransactionsScreen.h
   ├─ clsTransferScreen.h
   ├─ clsManageUsersScreen.h
   ├─ ...
   ├─ Clients.txt
   ├─ Users.txt
   ├─ TransferLog.txt
   └─ LoginRegister.txt
```

## 💾 Data Storage

The system uses text files as a simple local database:

- `Clients.txt`
- `Users.txt`
- `TransferLog.txt`
- `LoginRegister.txt`

## ▶️ Build & Run

### Visual Studio (Recommended)
1. Open `BankSystem2.vcxproj`
2. Build the solution
3. Run the project

### g++ (Example)
```bash
g++ -std=c++17 BankSystem2.cpp -o BankSystem
./BankSystem
```

## 🎯 Learning Goals

This project was built for practice in:

- Object-Oriented Programming (OOP)
- File handling in C++
- Console UI design
- Class-based modular architecture

## 📌 Notes

- This is a **training/educational project**.
- No license is specified for this repository.

## 👤 Author

**EhsanTahanO**
