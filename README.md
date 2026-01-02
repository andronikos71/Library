#  Library Management System (C++)

A simple **console-based Library Management System** written in **C++**, designed for **beginner users**.

This application allows you to manage a small collection of books directly from the terminal.

---

##  Features

With this program you can:
-  **Add a new book**
-  **View all books**
-  **Search for a book by ID**
-  **Edit book information**
-  **Delete a book**
-  **Exit the program safely**

---

##  Requirements

To run this program you need:
- A **C++ compiler** (`g++` recommended)
- A **terminal** (Command Prompt / PowerShell / Terminal)
- Basic keyboard input skills

 No external libraries are required.

---

##  Project Files

Make sure **all files are in the same folder**:

- main.cpp
- Book.h
- Book.cpp
- Library.h
- Library.cpp

**If a file is missing, the program will not compile**.

---

## How to Run the Program

### On **Windows**
```bash
library
```

### On **MacOs**
```bash
./library
```
##How to Use the Program

**When the program starts, a menu will appear:**

1. Add book
2. Display all books
3. Search book by ID
4. Edit book
5. Delete book
6. Exit

---

## Book Data

**Each book contains:**

- Title
- Author
- Year of publication
- Unique ID

### Important ***The ID must be unique.***
**Using the same ID more than once may cause incorrect results.**

---

## How the Program Works (Simple Explanation)

1. Books are stored in memory using dynamic arrays
2. The program uses classes (Book and Library)
3. Pointers are used to manage memory
4. Everything runs inside a loop-based menu
   
**No database or file storage is used.**

---

## Important Notes

- This is a console (terminal) application
- Data is not saved permanently when the program closes
- Designed for learning and educational purposes
- Best suited for beginner C++ users

---

## Beginner Tips

- If this is your first time using a C++ program:
- Do not worry about the code at first
- Compile and run the program
- Read the on-screen messages carefully
