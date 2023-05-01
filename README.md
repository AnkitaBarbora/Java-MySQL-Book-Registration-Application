# Book Registration System using Java and MySQL with XAMPP

This project is a Book Registration System built with Java and MySQL, using XAMPP as the local development environment. The system allows users to add, edit, delete, and search for books in a database. The user interface is implemented using Java Server Pages (JSP), and the data is stored in a MySQL database.

## Getting Started

To get started with the Book Registration System, you will need to have XAMPP installed on your machine. You can download XAMPP from the [Apache Friends website](https://www.apachefriends.org/download.html).

You will also need an IDE (Integrated Development Environment) such as Eclipse or IntelliJ IDEA to run the project.

## Setting up the Database

XAMPP comes with MySQL pre-installed, so you don't need to install it separately. To set up the database for the Book Registration System, follow these steps:

1. Start XAMPP and ensure that Apache and MySQL are running.
2. Open your web browser and go to `http://localhost/phpmyadmin`.
3. Click on the "New" button to create a new database.
4. Enter "bookstore" as the database name and click "Create".
5. Click on the "Import" tab and choose the `sql/bookstore.sql` file from the project folder. Click "Go" to import the table structure and data.

## Running the Application

To run the Book Registration System, follow these steps:

1. Clone the repository to your local machine.
2. Open the project in your IDE.
3. Build the project in your IDE to generate the WAR (Web Application Archive) file.
4. Rename "javacrud" as the name your database in the line 
// con = DriverManager.getConnection("jdbc:mysql://localhost:3307/javacrud", "root",""); 
in the Connect() function of the source code.
5. Start XAMPP and ensure that Apache and mySQL are running.
6. Click on run as java application in your IDE.

## Using the Application

Once the Book Registration System is running, you can use the following features:

- Add a new book: Fill out the form with the book information. Click "Save" to add the book to the database.
- Edit a book: Click on the "Edit" button next to a book to open the edit form. Make any changes and click "Save" to update the book in the database.
- Delete a book: Click on the "Delete" button next to a book to remove it from the database.
- Search for books: Enter a search term in the search box to search for books by title or author. Click "Search" to display the search results.

## Contributing

Contributions to the Book Registration System are welcome! If you have any bug reports, feature requests, or code improvements, please open an issue or pull request in the repository.
