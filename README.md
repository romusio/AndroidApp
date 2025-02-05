# AndroidApp #Dart #Flutter
a simple home library which allows you to add books, choose a genre, as well as an artist.
The main elements of your code:
MaterialApp:

The root widget that adjusts the theme and structure of the application.

In your code, it sets the application title and theme (blue color).

Scaffold:

A widget that provides the basic structure of the page (AppBar, Body, etc.).

TextField:

The text input field. In your code, it is used to enter the book title, author, and genre.

ElevatedButton:

The button that calls the _addBook method to add a book to the list.

ListView.builder:

Widget for displaying a list of books. It dynamically creates list items based on the books array.

StatefulWidget:

A widget that can change its state (for example, update the list of books when adding or deleting).

The Book model:

A class that describes the data structure for a book (title, author, genre).
