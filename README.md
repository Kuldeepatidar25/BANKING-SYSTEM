**Banking System Console-Based Mini Project**

**Introduction**
This is a console-based banking system implemented in C++ as a mini-project. The system allows users to perform basic banking operations such as opening an account, checking balance, depositing, withdrawing, closing, and viewing all accounts.

**How to Use**
1) Compile and Run:

Use a C++ compiler to compile the code. For example, using g++: **(g++ banking_system.cpp -o banking_system
)**

Run the executable:**(./banking_system
)**

2) Functionality:

Open an account by providing the first name,last name, and initial balance.
Check the balance by entering the account number.
Deposit and withdraw money from an account.
Close an account.
View details of all accounts.

3) File Handling:
The program uses file handling to store account information persistently in "Bank.data" file.
On program startup, existing account data is read from the file, and on exit, the data is written back to the file.

4) Console-Based Interface:
The entire interaction with the system is through the console, with a menu-driven approach.

5) Acknowledgment:
portions of the code were developed with reference to concepts learned in the **C++ Programming** course by **Abdul Bari**.

**Code Structure**

The code is structured into three classes:

**Account:**
Represents a bank account with attributes like account number, first name, last name, and balance.
Provides methods for deposit, withdrawal, and balance inquiry.

**Bank:**
Manages a collection of accounts using a map.
Performs operations like opening an account, checking balance, depositing, withdrawing, closing an account, and displaying all accounts.
Uses file handling to store and retrieve account data.

**Main:**
Implements the user interface with a menu-driven approach.
Handles user input to interact with the banking system.

**Error Handling**

The program includes error handling for insufficient funds during withdrawals.
Proper file handling to ensure the program can read and write account data without issues.


**Future Enhancements**

Improve user interface and input validation.
Add more advanced features such as interest calculation.
Implement user authentication and security features.
