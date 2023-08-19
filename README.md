# Library Management System Readme

## Introduction

The Library Management System is a comprehensive application designed to efficiently manage the resources of a library. This system is built using Java Swing with NetBeans as the Integrated Development Environment (IDE) and XAMPP for database management. The software comprises two primary panels: the user panel and the admin panel. The user panel enables library users to search for books, request book loans, and manage their borrowing history. The admin panel equips library staff with tools to oversee library resources, manage users, handle book issues, and more. The system also includes features for password recovery and user registration.

## Getting Started

1. Clone or download the repository to your local machine.
2. Open the project in NetBeans IDE.
3. Configure the XAMPP database settings for the application.
4. Compile and run the application.

## Features

### User Panel

Upon successful login, users gain access to the user panel with the following functionalities:

- Search for books using parameters like author, title, or category.
- Request a book loan by selecting the desired book and specifying the loan duration.
- Save borrowing history to a file for future reference.

### Admin Panel

The admin panel empowers library staff with extensive management capabilities:

- Add or remove users from the library system.
- Manage books by adding or removing them from the library inventory.
- Track and manage book issues and returns.
- Review and approve/reject user requests for book loans.
- Search for books using various criteria such as title, author, or publication year.

### Forgot Password Panel

The forgot password panel enables users to recover their password in case they forget it. The system securely manages password recovery through user-defined security questions or email verification.

### Signup Panel

The signup panel allows new users to register themselves with the library system. Once registered, users gain access to library resources and services.

## Code Explanation

### Login Page

The login page is the entry point of the software. Users are required to enter their username and password. The page utilizes Java Swing components to create an intuitive graphical user interface (GUI). Object-oriented concepts like polymorphism, inheritance, and exception handling are applied to ensure secure and efficient login functionality.

### User Panel

The user panel employs JDBC to manage data, such as reservations and borrowing history. Object-oriented principles enhance the modular structure and exception handling. Swing components facilitate user interaction with the GUI. Users can reserve books by entering book details and loan duration. Reservation details are stored in the database using JDBC.

### Admin Panel

The admin panel, designed for library staff, facilitates efficient management of library resources. It utilizes inheritance and polymorphism to extend the capabilities of the base Admin class. Features include adding/removing users and books, managing loan history, and approving user requests. The admin panel integrates a search functionality to retrieve book information from the MySQL database via SQL queries and JDBC.

### Export Data to a Text File

Users and administrators can export data to text files for record-keeping. The system uses the PrintWriter class to save book information to a text file. Robust exception handling ensures smooth data export and management.

### Object-Oriented Concepts

Object-oriented principles such as inheritance, polymorphism, and abstraction are crucial to the project's structure. Inheritance allows subclasses to inherit attributes and methods from the parent class. Polymorphism is used in the BookDetailsRetriever class to process different input parameters. Abstraction is employed to define common behavior shared among multiple classes, promoting code reuse and minimizing duplication.

## Conclusion

The Library Management System is a comprehensive application that streamlines library operations through its user-friendly interfaces, robust database management, and thoughtful implementation of object-oriented principles. By leveraging Java Swing, NetBeans IDE, and XAMPP, the system provides a holistic solution for library resource management, catering to both users and library staff.
