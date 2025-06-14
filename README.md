
 # Library Management System

A simple Java console application to manage a library of books. Users can add, display, search, issue, and return books using an interactive menu-driven interface.

---

## Features

- Add books with title and author.
- Display all books along with their availability status.
- Search books by title or author (case-insensitive, partial match).
- Issue books by book ID (mark as borrowed).
- Return issued books by book ID.
- Continuous menu-driven interaction until exit.

---

## Project Structure

- **Book.java** — Represents a book entity with attributes and methods to issue/return the book.
- **Library.java** — Manages a collection of books and provides operations like add, search, issue, return.
- **LibraryManagementSystem.java** — Main class with the user interface and program flow.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/LibraryManagementSystem.git
   Navigate to the project directory:
   cd LibraryManagementSystem
   Compile the Java files:

bash
Copy
Edit
javac LibraryManagementSystem.java
Run the program:

bash
Copy
Edit
java LibraryManagementSystem
Usage
Follow on-screen prompts to add books, display the list, search, issue, or return books.

Input the correct book ID for issuing or returning books.

Select option 7 to exit the program.

Sample Interaction
pgsql
Copy
Edit
--- Library Management Menu ---
1. Add Book
2. Display All Books
3. Search Book by Title
4. Search Book by Author
5. Issue Book
6. Return Book
7. Exit
Choose an option: 1
Enter book title: The Hobbit
Enter author name: J.R.R. Tolkien
Book added: ID: 1 | Title: The Hobbit | Author: J.R.R. Tolkien | Available
Possible Improvements
Persist book data between sessions (file/database).

Add user authentication for issuing books.

Implement due dates and fine calculations.

Create a graphical user interface (GUI).


