# BankEase: Console-Based Java Banking System

A fully functional **Banking Management System** built in Java using **OOP principles, collections, file handling, and JDBC**, culminating in a deployable backend app with MySQL integration.  

This project demonstrates Java fundamentals, Java 8 features, exception handling, multithreading, and backend deployment with persistent storage.

---

## 📌 Project Overview

BankEase is a console-based banking system that allows users to:

- Create accounts  
- Deposit and withdraw funds  
- Transfer money between accounts  
- View transaction history  

It also provides **admin functionalities**:

- View all users and their account statuses  
- Freeze/unfreeze accounts  
- Audit transaction logs  

The project emphasizes:

- **Java OOP principles**: classes, inheritance, interfaces, encapsulation  
- **Java 8 features**: lambdas, streams  
- **Concurrency**: simulating concurrent transactions with multithreading  
- **Data persistence**: MySQL integration using JDBC  
- **Robust exception handling** with custom business-rule exceptions  

---
## 🖼️ Visual Representation

Visual representation of BankEase’s structure and workflow:

![Bank System Diagram](Database/bank-application-diagram.png)


---

## ⚙️ Key Functionalities

### 1. Account Management
- Console-based user registration and login  
- Admin authentication and access controls  

### 2. Transaction Features
- Deposit, withdraw, transfer between accounts  
- Real-time balance checks and transaction history  

### 3. Data Handling
- JDBC integration for persistent storage  
- File I/O or in-memory options for testing or low-resource scenarios  

### 4. Admin Controls
- View all users and their account statuses  
- Freeze/unfreeze accounts  
- Audit transaction logs  

---

## 🛠️ Technologies Used

- Java 8+  
- MySQL  
- JDBC  
- File I/O  
- Multithreading  
- JUnit (for unit testing)  

---

## 📝 Project Structure

1. **Project Setup & Design**
   - Packages for Account Operations, Admin Panel, Transactions  
   - UML diagrams for design reference  

2. **OOP-Based Account Operations**
   - Classes: `User`, `BankAccount`, `Admin`  
   - Inheritance, polymorphism, encapsulation  
   - Method overloading for varied operations  

3. **Transactions & Statements**
   - Core methods: `deposit()`, `withdraw()`, `transfer()`  
   - Transaction logs with timestamps  
   - Concurrent transaction simulation  

4. **JDBC Integration**
   - Connection to MySQL database  
   - CRUD operations for users, accounts, transactions  
   - Secure storage of database credentials  

5. **Functional Programming**
   - Lambda expressions for concise callbacks  
   - Stream API to filter, sort, and aggregate transactions  

6. **Testing & Exception Handling**
   - Unit tests with JUnit  
   - Edge case handling: overdrafts, invalid inputs, negative deposits  
   - Custom exceptions like `InsufficientFundsException`  

7. **Deployment**
   - Packaged as a runnable JAR or Docker container  
   - Can be deployed to a remote MySQL instance (Railway, PlanetScale, etc.)  

