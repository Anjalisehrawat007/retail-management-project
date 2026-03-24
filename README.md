# 🛒 Retail Management System (C++ Project)

## 📌 Project Overview

This project is a **Retail Management System** developed using C++. It is designed to simulate basic retail operations such as managing products, inventory, and billing.

The system uses file handling and Object-Oriented Programming (OOP) concepts to store and manipulate product data efficiently.

---

## ⚠️ Important Warning

* This program uses the `conio.h` header file, which may **not be supported on Linux/macOS (Clang-based systems)**.
* It is recommended to **compile and run the program only on Windows systems**.

### ▶️ Execution Instructions

* **Windows:**

  ```id="lq0y6p"
  main
  ```
* **Linux (if compatible):**

  ```id="9kwx6g"
  ./main.exe
  ```

A precompiled executable file `main.exe` is provided as a backup in case compilation fails.

---

## 🧭 Navigation Guide

### 📄 Files Included

* `README.md` → Project documentation
* `main.exe` → Precompiled executable file

### 📁 Folders

* **Project/**
  Contains:

  * `main.cpp`
  * Header files
  * Compiled executable

* **Team Docs/**
  Contains:

  * Project-related documents
  * Project demonstration video

---

## ⚙️ Features

* Add new products
* Delete existing products
* Update product details
* Display product information
* File-based storage system

---

## 🧠 Concepts Used

* Object-Oriented Programming (OOP)
* File Handling
* Vectors (Dynamic Data Storage)
* Modular Programming using Header Files

---

## ⚠️ Issues Faced & Solutions

### 1️⃣ Use of Vectors

**Issue:**
Storing and managing multiple products efficiently.

**Solution:**
Used vectors to store each product as an object in memory, allowing easy operations such as Add, Delete, Update, and Display.
This helped in properly implementing OOP concepts instead of simple file handling.

---

### 2️⃣ Escape Key Ambiguity

**Issue:**
Handling escape key input during execution.

**Solution:**
Resolved using `_getch()` function from `<conio.h>` and ASCII value `27` for detecting the Escape key.

---

### 3️⃣ Linking Billing and Inventory

**Issue:**
Connecting billing module with inventory data stored in files.

**Solution:**
Linked billing header file with inventory management to access and update `product.txt` file efficiently.

---

## 🚀 Future Improvements

* Make the system platform-independent (remove `conio.h`)
* Add graphical user interface (GUI)
* Improve file handling with database integration
* Enhance user interaction and error handling

---

## 👥 Contributors

* Anjali Sehrawat


---

## 📜 Note

This project is developed for academic purposes and demonstrates the application of OOP concepts in a real-world scenario.

---
