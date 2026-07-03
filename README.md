Personal Finance Tracker

A console-based personal finance management application built with Java Core. The project allows users to track income and expenses, monitor their current balance, and manage financial records without using a database.

Features

* Add income transactions
* Add expense transactions
* View all transactions
* Edit existing transactions
* Delete transactions
* Search transactions
* Sort transactions
* View current balance
* Display financial statistics
* Save and load data from a file
* Input validation and exception handling

Technologies

* Java Core
* Object-Oriented Programming (OOP)
* Collections Framework
* Java File I/O
* Exception Handling
* LocalDate / LocalDateTime
* Stream API

Project Structure

src/
├── model
├── repository
├── service
├── ui
├── util
└── Main.java

Data Storage

The application stores all data in a local file.

The file contains:

* Current balance
* Transaction history

Every time a transaction is added, edited, or deleted, the current balance is updated and the data is saved.

Main Menu

1. Add Income
2. Add Expense
3. View Transactions
4. Edit Transaction
5. Delete Transaction
6. Search
7. Sort
8. Statistics
9. Current Balance
0. Exit

Future Improvements

* Financial goals
* Monthly budget planning
* Recurring transactions
* Multiple accounts (Cash, Card, Savings)
* Database integration
* JavaFX desktop interface
* Spring Boot REST API
* Web application

Purpose

The main goal of this project is to practice Java Core by implementing a real-world application using clean architecture, file storage, and object-oriented design principles.