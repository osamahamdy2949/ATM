# ATM
A C++ console-based ATM system simulating banking operations like login, deposits, withdrawals, and balance checking with persistent client data.

# 🏦 ATM Console System in C++

A **C++ console-based ATM system** that simulates a real-world banking environment. Users can **log in**, **check balances**, **deposit money**, and **withdraw funds**. The system persists client data in a file, allowing multiple sessions and realistic banking operations.

---

## 🌟 Features

- **Secure Login:** Users authenticate with Account Number and PIN.  
- **Quick Withdraw:** Predefined withdrawal options for convenience.  
- **Normal Withdraw:** Custom withdrawal amounts (multiples of 5).  
- **Deposit Funds:** Add money to the account with confirmation.  
- **Check Balance:** Display current account balance.  
- **Data Persistence:** Client information is saved in `Clients.txt`.  
- **Transaction Validation:** Ensures sufficient funds for withdrawals.  
- **Interactive Console Interface:** Colored feedback for correct/incorrect actions.

---

## 📂 Project Structure

ATM_System/
├─ ATMSystem.cpp # Main C++ source code
├─ Clients.txt # Stores all client information
├─ README.md # Project documentation


---

## 📄 Client Data Format (`Clients.txt`)

Each client record is stored as a **single line** using a separator `#//#`:

AccountNumber#//#PinCode#//#Name#//#Phone#//#AccountBalance


**Example:**

123456#//#1234#//#Osama Hamdy#//#01008355715#//#10000.0


- `AccountNumber`: Unique client ID  
- `PinCode`: 4-digit PIN  
- `Name`: Full name  
- `Phone`: Contact number  
- `AccountBalance`: Current account balance  

---

## ⚙️ Requirements

- Windows OS (uses `system("cls")` and `system("pause")`)  
- C++ Compiler (C++11 or newer)  
- Console application environment (e.g., Visual Studio, Code::Blocks)

---

## 🚀 How to Run

1. Clone the repository or download the source code.
2. Open the project in a **C++ IDE**.
3. Compile and run `ATMSystem.cpp`.
4. Login using an existing account in `Clients.txt` or add new accounts manually.
5. Follow on-screen instructions for transactions.

---

## 📝 Usage Example

Login Screen
Enter Account Number: 123456
Enter Pin: 1234

ATM Main Menu:
[1] Quick Withdraw
[2] Normal Withdraw
[3] Deposit
[4] Check Balance
[5] Logout


- Quick Withdraw subtracts preset amounts from your balance.  
- Normal Withdraw allows custom amounts in multiples of 5.  
- Deposit adds funds with confirmation.  
- Balance displays current funds.  

---

## 💡 Future Improvements

- **GUI Version:** Implement a graphical interface for a better user experience.  
- **Encryption:** Encrypt client data for security.  
- **Transaction History:** Keep logs for deposits and withdrawals.  
- **Multi-User Support:** Handle concurrent sessions.  
- **Error Handling:** Enhance input validation and exception management.

---

## 📌 Notes

- This is a **console-based learning project** aimed at practicing **C++ programming, file handling, and basic banking logic**.  
- Suitable for beginners and intermediate learners to understand structured programming and OOP concepts in C++.
