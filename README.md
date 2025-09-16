# Create-a-fully-functional-ATM-interface-using-C-
first task
ATM-Interface-Cpp/
│── atm.cpp                 # Full C++ source code
│── README.md               # Project overview (for GitHub)
│── Report.md               # Detailed project report
│── sample_output.txt       # Demonstration of program run
│── accounts.txt            # (auto-generated at runtime)
│── transactions.txt        # (auto-generated at runtime)

# ATM Interface in C++

This is a **console-based ATM simulation** built in C++ as a mini-project.  
It supports account creation, login with PIN, deposits, withdrawals, transfers, mini-statements, PIN changes, and an admin view.

## Features
- Account creation with auto-generated ID
- PIN-based login
- Deposit, Withdraw, Transfer
- Mini-statement (last 5 transactions)
- Change PIN
- Admin login (PIN: 9999) to view all accounts
- Data persistence using text files

## Project Structure
- `atm.cpp` → Main source code
- `Report.md` → Detailed first project report
- `sample_output.txt` → Demonstration of program run
- `accounts.txt` & `transactions.txt` → auto-generated during runtime

## Compilation & Run
```bash
g++ -std=c++17 atm.cpp -o atm
./atm   # Linux / macOS
atm.exe # Windows

