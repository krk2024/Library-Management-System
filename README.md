# Library-Management-System
This SQL script sets up a Library Management System by creating and populating tables for publishers, books, authors, borrowers, library branches, book copies, and book loans. It includes foreign key relationships to ensure data integrity and uses AUTO_INCREMENT for primary keys where needed.
# Library Management System – SQL Database

## 📌 Project Overview
This project implements a relational **Library Management System** using MySQL. It covers complete database design, creation, and data population for managing books, publishers, authors, borrowers, library branches, book loans, and book copies.

## 🏗️ Database Structure

- **tbl_publisher** – Stores publisher details
- **tbl_book** – Book information with foreign key to publisher
- **tbl_library_branch** – Library branch data
- **tbl_borrower** – Borrower details
- **tbl_book_loans** – Tracks which borrower borrowed which book from which branch
- **tbl_book_copies** – Number of copies of each book in each branch
- **tbl_book_authors** – Author details linked to books

## 🔑 Key Features

- Normalised schema with **referential integrity**
- Use of **foreign key constraints** with `ON DELETE/UPDATE CASCADE`
- Use of **AUTO_INCREMENT** primary keys
- Populated with realistic data entries for testing

## 🧪 Sample Queries

- Retrieve books by specific publisher  
- Track book loans by borrower and branch  
- View available book copies across branches

## 🛠️ Technologies Used

- **SQL**
- **MySQL** (tested on MySQL 8+)

## 📂 How to Use

1. Create the database:  
   ```sql
   CREATE DATABASE db_LibraryManagement;
   USE db_LibraryManagement;
