# Library Management System

This is a simple library management system built using Python and Tkinter for the GUI. It allows users to perform basic library operations such as adding book details, deleting books, viewing the book list, issuing books to students, and returning books.

## Features

- **Add Book Details:** Add new books to the library database with details like title, author, ISBN, etc.
- **Delete Book:** Remove books from the library database based on their ID or other criteria.
- **View Book List:** Display a list of all books currently available in the library.
- **Issue Book to Student:** Allow librarians to lend books to students by updating the database accordingly.
- **Return Book:** Update the database when a student returns a book to the library.

## Requirements

- Python 3.x
- Tkinter (should come with Python by default)
- Pillow (for image processing, can be installed via `pip install Pillow`)
- mysql-connector-python (for MySQL database connection, can be installed via `pip install mysql-connector-python`)

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/library-management-system.git
2. **Install dependencies:**
   ```bash
   pip install Pillow mysql-connector-python
3.Make sure you have a MySQL database set up with the appropriate tables. You can use the provided SQL script (library_database.sql) to create the necessary tables.

4. **Modify the database connection settings in the Python code (main.py) to match your MySQL server configuration:**
   ```bash
   host = "localhost"
   user = "your_mysql_username"
   password = "your_mysql_password"
   database = "your_database_name"
5. **Run the Script:**
   ```bash
   python main.py
## Screenshots
https://github.com/abdullahfahim2/Library-Management-System/blob/main/Screenshot%202024-04-12%20002134.png
## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests to improve the functionality or add new features.

## Contributor
- [Md Abdullah Al Fahim](https://github.com/abdullahfahim2)
