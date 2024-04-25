# library-management-system

This is a Library Management System implemented in C++. The system provides functionalities to manage a library's resources, including books, borrowers, borrowing, returning, and administrative tasks.

## Features

- Book Management: Allows librarians to add, update, and remove books from the library inventory. Each book record includes details such as title, author, genre, ISBN, and availability status.
- Member Management: Enables librarians to register library members, update their information, and deactivate or remove member accounts if necessary. Member records include details such as name, contact information, and membership status.
- Borrowing and Returning: Facilitates the borrowing and returning of books by members. Members can borrow books if they are available and return them within the specified loan period.
- Fine Calculation: Calculates fines for overdue books based on predefined rules and manages the fine payment process.
- Reservation System: Allows members to reserve books that are currently unavailable. Once the reserved book becomes available, the system notifies the member to pick it up.
- Reporting: Generates reports on various library metrics, including book availability, member activity, overdue books, and fines collected.
- User Authentication: Implements user authentication to ensure that only authorized personnel can access administrative functions.
