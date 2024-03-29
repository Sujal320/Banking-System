# Banking-System
This program provides a basic framework for managing bank accounts and performing typical banking operations while demonstrating exception handling techniques in Java.

This Java program simulates a simple banking system with classes representing bank accounts, custom exceptions, and a bank management system.

Custom Exception Classes:
InsufficientFundsException, InvalidAccountNumberException, and IncorrectPINException represent specific error conditions in the banking system.

Account Class:
Represents a bank account with attributes such as account number, account holder name, account balance, and PIN.
Provides methods for depositing money, withdrawing money (handling insufficient funds), verifying PIN, and retrieving account details.

Bank Class:
Manages bank accounts using an array of Account objects.
Provides methods for creating accounts, finding accounts by account number, depositing money, withdrawing money (handling insufficient funds), checking account balance, and authenticating account.

BankingSystem Class (Main Class):
Contains the main method where you create an instance of the Bank class.
Demonstrates creating accounts, depositing money, withdrawing money, checking account balance, and authenticating users using try-catch blocks to handle exceptions gracefully.
