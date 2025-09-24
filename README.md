# 🏡 Real Estate Sales Management System (RESMS)

A **C++ based Real Estate Sales Management System (RESMS)** designed to streamline property, agent, and sales record management.  
This project demonstrates **Object-Oriented Programming (OOP)** principles, file handling, modular design, and secure login management.  

---

## 📖 Table of Contents
1. [About the Project](#about-the-project)  
2. [Features](#features)  
3. [System Design](#system-design)  
4. [Project Structure](#project-structure)  
5. [Installation & Usage](#installation--usage)  
6. [Sample Data](#sample-data)  
7. [Future Enhancements](#future-enhancements)  
8. [Contributing](#contributing)  
9. [License](#license)  
10. [Acknowledgements](#acknowledgements)  

---

## 📌 About the Project
The **Real Estate Sales Management System** is aimed at providing an easy-to-use tool for managing:  
- **Agents** who deal in properties  
- **Properties** with details like location, size, price  
- **Sales Records** that map agents to their sales  

This project is especially useful for students learning **C++ OOP concepts** such as:  
- Classes & Objects  
- Inheritance  
- Encapsulation  
- File I/O  
- Modular programming  

---

## ✨ Features
✔️ **Agent Management**  
   - Add, update, and list all registered agents  

✔️ **Property Management**  
   - Record new property details  
   - Search properties by location, size, or price  
   - Display available inventory  

✔️ **Sales Tracking**  
   - Record transactions between agents and buyers  
   - Generate simple sales reports  

✔️ **Login & Authentication**  
   - User authentication handled via `a1login.cpp`  
   - Credentials stored in `passwords.in`  

✔️ **File Handling**  
   - Input and output operations using `data.in` for persistent data  

---

## 🏗 System Design
The project is divided into multiple classes and modules:

- **Agent Class** (`Agent.h`) – stores agent details such as ID, name, and performance.  
- **Property Class** (`Property.h`) – manages property attributes like size, BHK, location, and price.  
- **Data Handling** (`Data.h`, `data.in`) – persistent storage of sales and property data.  
- **Node/List Structures** (`nodo.h`, `lista.h`) – used to manage linked list structures for efficient data handling.  
- **Authentication System** (`a1login.cpp`, `passwords.in`) – provides secure login access.  

---

## 📂 Project Structure
```bash
sales/
│
├── Agent.h        # Agent class definition
├── Data.h         # Data management header
├── Property.h     # Property class definition
├── lista.h        # Linked list implementation
├── nodo.h         # Node structure for lists
│
├── project.cpp    # Main entry point
├── a1login.cpp    # Login system
│
├── data.in        # Sample property/agent data
├── passwords.in   # Sample login data
│
├── makefile       # Build automation
├── project.exe    # Precompiled binary (Windows)
└── README.md      # Documentation
