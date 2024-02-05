# Updated Library System

## Overview

This updated version of the Library System is implemented in C++ and includes enhancements such as encapsulation, a `Book` class, and improved code organization. The program allows users to manage a collection of books by providing features like adding books, searching for books by author or title, displaying sorted books, and quitting the system.

## Features

1. **Add Books (Choice 1):**
   - Users can add new books to the library by entering details such as title, author, and publication year.

2. **Search for an Author (Choice 2):**
   - Users can search for books based on the author's last name. The system displays books by the specified author along with their publication years and positions.

3. **Search for by Book Title (Choice 3):**
   - Users can search for books based on the title. The system displays books matching the specified title along with their authors, publication years, and positions.

4. **Display Books (Choice 4):**
   - Displays the list of books sorted by the author's last name using the Selection Sort algorithm.

5. **Quit (Choice 5):**
   - Allows users to exit the Library System.

## Code Organization

### `Book` Class

The `Book` class encapsulates the properties and behavior of a book. It includes member functions for getting and setting attributes, as well as additional functions like `getAuthorLastName()` and `display()` for convenience.

### Sorting Algorithm

The `SelectSort` function uses the Selection Sort algorithm to sort the list of books by the author's last name in ascending order.

### Search Operations

- `bsearch`: Performs a binary search to find books by a specified author and returns their positions.
- `SearchTitle`: Searches for books based on the title and returns the position if found.

## Usage Instructions

1. **Compile and Run:**
   - Compile the program using a C++ compiler.
   - Run the executable to start the Library System.

2. **Menu Selection:**
   - Choose a menu option (1-5) to perform the desired operation.

3. **Add Books:**
   - Enter the details for a new book, including title, author, and publication year.

4. **Search for an Author:**
   - Enter the last name of the author to search for books. The system displays books by the specified author.

5. **Search for by Book Title:**
   - Enter the title of the book to search for. The system displays books matching the specified title.

6. **Display Books:**
   - Displays the list of books sorted by the author's last name.

7. **Quit:**
   - Choose option 5 to exit the Library System.

## Additional Information

- This program was authored by Filiz İpek Oktay.

Feel free to explore, modify, and adapt this program according to your needs. If you have any questions or suggestions, please reach out to the program's author.
