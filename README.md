## Library Management System

This project is a Library Management System developed using **Python**, **Tkinter**, and **SQLite3**. It provides a simple GUI interface to manage books in a library, including adding, updating, and removing records. Additionally, the system allows you to change the availability status of books with a single click.

## Features

- **Add New Records**: Insert a new book into the library.
- **Update Book Details**: Modify existing book information.
- **Delete Book Records**: Remove a book from the library database.
- **Clear Fields**: Reset the input fields for adding new books.
- **Change Book Availability**: Update the status of a book (Available/Issued).
- **View Book Inventory**: Displays all the books available in the library in a table view.
- **Delete Full Inventory**: Remove all books from the database with a single command.

## Technologies Used

- **Python**: Programming language for building the application.
- **Tkinter**: For the GUI interface.
- **SQLite3**: Database to store the library's book records.

## Installation

1. Clone the repository or download the project files.

   ```bash
   git clone https://github.com/yourusername/library-management-system.git
2. Navigate to project Directory
   ```bash
   cd library-management-system
3. Install Dependencies
   ```bash
   pip install tk
   
 ## Usage
1. Run the `library_management_system.py` file.
   ```bash
   python library_management_system.py
   
## Inserted Books

| Book Name               | Book ID | Author               | Status    | Issuer Card ID |
|-------------------------|---------|----------------------|-----------|----------------|
| To Kill a Mockingbird    | BK001   | Harper Lee           | Available | N/A            |
| 1984                    | BK002   | George Orwell        | Available | N/A            |
| The Great Gatsby         | BK003   | F. Scott Fitzgerald  | Available | N/A            |
| The Catcher in the Rye   | BK004   | J.D. Salinger        | Issued    | CID123         |
| Moby Dick                | BK005   | Herman Melville      | Available | N/A            |

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code.

## Author
Havish Gadey
