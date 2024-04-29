# Library Management System

This is a simple library management system implemented in C++. It allows managing books and users in a library, including functionalities like adding books, searching for books by prefix, printing who borrowed a book by name, adding users, allowing users to borrow and return books, and printing all users with their borrowed books.

## Features

- Add books to the library.
- Search for books by prefix.
- Print who borrowed a book by its name.
- Print the library by book ID.
- Print the library by book name.
- Add users to the library.
- Allow users to borrow books.
- Allow users to return books.
- Print all users with their borrowed books.

## Usage

1. **Compile**: Compile the `main.cpp` file using any C++ compiler. For example:
   1. g++ main.cpp -o library
2. **Run**: Run the compiled executable:

3. **Menu Options**: Follow the menu options to perform various operations:
- **Add book**: Add a new book to the library.
- **Search book by prefix**: Search for books by their names using a prefix.
- **Print who borrow book by name**: Print the users who borrowed a specific book by its name.
- **Print library by id**: Print all books in the library sorted by book ID.
- **Print library by name**: Print all books in the library sorted by book name.
- **Add user**: Add a new user to the library.
- **User borrow book**: Allow a user to borrow a book from the library.
- **User return book**: Allow a user to return a borrowed book to the library.
- **Print Users**: Print all users in the library with the books they borrowed.
- **Exit**: Exit the program.

## Example

```$ ./library

Library Menu:

Add book
Search book by prefix
Print who borrow book by name
Print library by id
Print library by name
Add user
User borrow book
User return book
Print Users
Exit
Enter Your Choice : 1
Enter book info Id, Name, Quantity: 1 C++ Programming 10```
