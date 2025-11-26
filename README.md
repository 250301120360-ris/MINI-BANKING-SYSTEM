# 🏦 Mini Banking System (C Language)

A simple **file-based banking system** built using **pure C language**. This project is great for beginners who want to learn about:

* File handling
* Structures
* CRUD operations
* Basic authentication
* Console-based application development

---

## 📌 Features

### ✅ **1. Create Account**

* User enters account number, name, password, and initial deposit
* Data is saved in a binary file (`bank_records.dat`)

### ✅ **2. Delete Account**

* Deletes account permanently from the file
* Requires correct account number and password

### ✅ **3. Deposit Money**

* Login required
* Updates balance in the file

### ✅ **4. Withdraw Money**

* Login required
* Checks for sufficient balance

### ✅ **5. Money Transfer**

* Login required
* Transfer between two accounts
* Updates both balances in the file

### ✅ **6. Check Balance**

* Shows account holder's name and balance
* Login required

### ✅ **7. List All Accounts**

* Displays all accounts stored in the file

---

## 🗂️ Project File Structure

```
/mini-banking-system
│── bank_records.dat      # Auto-created
│── main.c                # Project source code
│── README.md             # Documentation
```

---

## 🛠️ How to Compile & Run

### **Step 1: Compile**

```bash
gcc main.c -o bank
```

### **Step 2: Run**

```bash
./bank
```

---

## 📷 Program Menu

```
===== MINI BANKING SYSTEM =====
1. Create Account
2. Delete Account
3. Deposit Money
4. Withdraw Money
5. Transfer Money
6. Check Balance
7. List All Accounts
8. Exit
```

---

## 📌 Important Notes

* The program stores all account data in a **binary file**.
* Passwords are stored as plain text (simple project limitation).
* Account number must be unique.
* Transfer feature requires both accounts to exist.

---

## 🚀 Future Improvements

You can upgrade this project by adding:

* Transaction history
* Admin dashboard
* Encrypted password storage
* Phone-number/email-based login
* Colorful UI with ANSI escape codes

---

## 🤝 Contributing

Feel free to fork this repository and improve the project.

---

## ⭐ If you like this project

Give it a **star on GitHub** and share it with others learning C!

---

**Made with ❤️ using C Language**
<img width="570" height="474" alt="image" src="https://github.com/user-attachments/assets/82089ac1-6d24-4a65-a3af-08a93ca918f7" />

