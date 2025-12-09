# 📚 CLI Book Library

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> A lightweight Library Management System built with pure Python, featuring CRUD operations and file-based data persistence.

## 📖 About The Project

**CLI Book Library** is a console-based application designed to manage book collections efficiently. It serves as a comprehensive implementation of Python's fundamental capabilities, specifically focusing on file handling and data manipulation without relying on SQL databases.

This project demonstrates a solid understanding of:
* **Modular Programming:** Organizing code into packages (`CRUD`) and modules.
* **File I/O:** Reading, writing, and parsing raw `.txt` files as a database.
* **String Manipulation:** Formatting data for neat table displays and storage.

## ✨ Key Features

* **CRUD Operations:** Create, Read, Update, and Delete book records.
* **📂 Text-Based Database:** Uses `library.txt` to persist data, manually handling delimiters and data parsing.
* **🆔 Auto-Generated Keys:** Generates random unique Primary Keys (PK) for each book entry.
* **🖥️ Clean Console UI:** Features responsive tables and cross-platform screen clearing (Windows/Linux).
* **🔍 Search & Validation:** Validates user input (e.g., year format) and searches data by index.

## ⚙️ Project Structure

The project is structured as a Python Package to ensure clean code separation:

```text
├── main.py             # Entry point (Game Loop & System Check)
└── CRUD/               # APPLICATION PACKAGE
    ├── __init__.py     # Package initialization
    ├── Database.py     # Setup & DB initialization
    ├── Operasi.py      # Core logic (CRUD & formatting)
    ├── View.py         # Console UI & Input handling
    └── Util.py         # Helper functions (Random ID gen)
````

## 🚀 Getting Started

### Prerequisites

  * Python 3.x installed.

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/hafidzrafi/CLI-BookLibrary.git
    ```
2.  Navigate to the directory:
    ```bash
    cd CLI-BookLibrary
    ```
3.  Run the application:
    ```bash
    python main.py
    ```

## 🎮 Usage Guide

Once the application starts, you will see a menu:

1.  **Lihat Koleksi (Read):** Displays all books in a formatted table.
2.  **Tambah Koleksi (Create):** Adds a new book title, author, and year.
3.  **Ubah Koleksi (Update):** Edits specific details of an existing book.
4.  **Hapus Koleksi (Delete):** Permanently removes a book from the database.

*Note: The application automatically saves changes to `library.txt` upon exit.*

## 📝 License

Distributed under the MIT License.

-----

*Created by Fizz*
