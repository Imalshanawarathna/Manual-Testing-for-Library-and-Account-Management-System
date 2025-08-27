# Manual-Testing-for-Library-and-Account-Management-System

### 👋 Welcome to the QA Testing Project Readme!

This repository contains the manual testing documentation for two key projects: a **Bank Management System** and a **Library Management System**. 🏦📚

The goal of this documentation is to provide a clear, step-by-step guide to the testing process, covering a wide range of scenarios from basic functionality to security and error handling. Each test case is designed to validate a specific feature and ensure the software is reliable and bug-free. ✅

---

### **📋 Bank Management System (BMS)**

The BMS testing plan focuses on validating core financial operations. We've covered the entire lifecycle of an account, from creation to deletion, and all transactions in between.

#### **Key Areas Tested:**

* **Account Management:** 💳
    * Creating new accounts with valid and invalid data.
    * Updating and deleting existing accounts.
* **Transaction Management:** 💰
    * Depositing and withdrawing funds.
    * Handling insufficient balance scenarios to prevent overdrafts. 🚫
* **Fund Transfers:** ➡️⬅️
    * Validating transfers between accounts.
    * Testing for insufficient funds and invalid recipient errors.
* **Loan Management:** ✍️
    * Applying for loans with both valid and invalid details.

---

### **📚 Library Management System (LMS)**

The LMS testing plan is designed to ensure a smooth and reliable experience for both users and administrators. It covers user registration, book management, and the borrowing/returning process.

#### **Key Areas Tested:**

* **User Management:** 🧑‍💻
    * Registering new users and validating their details.
    * Updating user information.
* **Book Search & Borrowing:** 🔍
    * Searching for books by title or author.
    * Borrowing available books and preventing the borrowing of books already checked out. 🔒
* **Book Returns:** ↩️
    * Returning borrowed books.
    * Preventing users from returning books they didn't borrow, a key security check. 🛡️
* **Borrowing History:** 📖
    * Viewing a user's complete history of borrowed and returned books.

---

### **🚀 How to Use This Document**

This documentation is structured like a formal test plan. You can use it as a reference for your own projects by following the same format:

1.  **Test Case ID:** A unique identifier.
2.  **Test Scenario:** A brief description of what you're testing.
3.  **Steps:** The exact actions to perform.
4.  **Expected Result:** What the system should do.
5.  **Actual Result:** What the system actually did.
6.  **Pass/Fail:** The final outcome.

Happy Testing! 👍
