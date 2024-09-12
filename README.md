# Library System Project

This project implements a **Library System** that manages books and users. The system supports typical operations such as adding books, searching, borrowing, and returning books.

## Features

- **Book Management**:
  - Add books with an ID, name, and quantity.
  - Search books by name prefix.
  - List books ordered by either ID or name.
  - Track borrowed books and the users who borrowed them.
  
- **User Management**:
  - Add users with an ID and name.
  - Borrow books (if available) and update the quantity of the book.
  - Return books and update the system accordingly.
  - Optional: Add additional user details like email and address, and list borrowed books per user.

## How It Works

### Menu
The system starts by displaying a menu where the admin can:
1. Add a book
2. Search for a book
3. List books
4. Add a user
5. Borrow a book
6. Return a book
7. List borrowed books by users
8. View users who borrowed a specific book

### Book Operations
- **Adding a Book**: 
  The admin can add a book by specifying its ID, name, and quantity. Example:  
  `ID: 101`, `Name: CppHowToProgram`, `Quantity: 7`.
  
- **Searching for a Book**:
  The system allows searching by a **prefix** of the book's name. For example:
  - Searching for "Cpp" will return books like `CppHowToProgram`, `CppForDummies`.
  
- **Listing Books**:
  The system lists all books and allows sorting by **name** or **ID**.

- **Tracking Borrowed Books**:
  The system tracks the users who have borrowed specific books.

### User Operations
- **Adding a User**: 
  Each user has an ID and name. Additional details like email and address can be added.

- **Borrowing a Book**:
  Users can borrow books if there are available copies. If the book is out of stock, the system will notify the admin.

- **Returning a Book**:
  Users can return books, and the system will update the available quantity accordingly.

## Requirements
- **C++ Compiler**: The project requires a working C++ compiler (e.g., GCC, Clang).
- **Development Environment**: Any C++-supported IDE or text editor (e.g., Visual Studio, Code::Blocks).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Abdrlrahman-Mansour/Library-System.git
