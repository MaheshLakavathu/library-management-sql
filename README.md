# 📚 Library Management System – SQL Schema

## 📝 Description
This project presents a basic **database schema** for a Library Management System. The system is designed to manage books, authors, members, staff, and borrow transactions using **MySQL**.

---

## 🗂️ Tables

- **Authors** – Stores author details.
- **Books** – Stores book records, linked to authors.
- **Members** – Stores member data who can borrow books.
- **Staff** – Stores staff information.
- **Borrowing** – Logs borrowing activities between members and books.

---

## 🔗 Relationships

- One **Author** can write many **Books** (1:N)
- One **Member** can borrow many **Books** through **Borrowing** (1:N)
- One **Book** can appear in many **Borrowing** records (1:N)

---

## ⚙️ Tools Used

- **MySQL Workbench** – For writing and executing SQL.
- **Graphviz** – To generate the ER diagram.
- **GitHub** – For version control and submission.

---

## 📎 Files Included

- `schema.sql` – SQL script to create the database schema.
- `library_er_diagram.png` – ER diagram showing table relationships.
- `README.md` – Project overview.

---

## 🚀 How to Run

1. Open MySQL Workbench or your preferred SQL tool.
2. Run the `schema.sql` file to create tables.
3. Use the ER diagram for reference when inserting or querying data.

---


