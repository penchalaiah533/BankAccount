# Bank Account Simulation (Java OOP)

## 📌 Objective
This project simulates a simple **bank account system** using Java's **Object-Oriented Programming (OOP)** concepts.  
It allows the user to perform basic banking operations such as deposits, withdrawals, balance checks, and viewing transaction history.

---

## 🛠 Tools & Technologies
- **Java** (JDK 17 or higher recommended)
- **VS Code / IntelliJ IDEA**
- **Terminal / Command Prompt**

---

## 📂 Features
- Create a new bank account with an account number, holder name, and initial balance.
- Deposit money into the account.
- Withdraw money (with balance check).
- Check current balance.
- View all past transactions.
- Display account details.

---

## 📜 Class Structure
### `Account` Class
- **Fields**:
  - `accountNumber` (final)
  - `accountHolder` (final)
  - `balance`
  - `transactionHistory` (ArrayList)
- **Methods**:
  - `deposit(double amount)`
  - `withdraw(double amount)`
  - `checkBalance()`
  - `printTransactionHistory()`
  - `displayAccountDetails()
