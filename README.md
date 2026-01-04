# Python-Banking-System
A Python-based Bank Account Management System

Overview

This project is a menu-driven Bank Account Management System developed using Python. It is a command-line application that simulates basic banking operations in a simple and secure manner. The system allows users to manage accounts, perform transactions, and maintain transaction records with proper validation and error handling.

Key Functionalities
1. Account Creation

The system allows users to open a new bank account by providing essential details. Each account is uniquely identified using a PAN number to prevent duplicate entries. The system automatically generates a unique account number along with login credentials such as username and password.

2. Secure Account Access

Users can securely access their account by entering valid login credentials. Authentication ensures that only authorized users can view account details or perform banking operations.

3. Banking Transactions

The application supports essential banking transactions including deposits, withdrawals, and fund transfers. Balance validation is performed before every transaction to prevent invalid operations such as overdrawing an account.

4. Transaction History (Passbook)

Every transaction is recorded with details such as date and time, transaction type, amount, and updated balance. This passbook feature helps users track their complete account activity in an organized manner.

5. Data Persistence & Safety

All account and transaction data is stored using file handling, ensuring that information is retained even after the program is closed. Error handling mechanisms are implemented to manage invalid inputs and runtime errors smoothly.

Technologies & Concepts Used

Python – Core programming language

File Handling – To store account and transaction data

random module – For generating unique account numbers and credentials

datetime module – For recording transaction timestamps

Dictionaries & Functions – For efficient data management

Exception Handling – To ensure stability and reliability

Purpose of the Project

This project is designed to strengthen understanding of Python fundamentals and demonstrate how real-world banking systems can be implemented using basic programming concepts in a structured way.


