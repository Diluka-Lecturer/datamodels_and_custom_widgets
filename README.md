# Flutter Lab: Data Models & Custom Widgets

In this lab, you will learn how to create a simple Dart data model and display its data using a reusable custom Flutter widget.

## Prerequisites

1. Clone this repository to your local machine.
2. Run `flutter pub get` in your terminal.
3. Ensure you have an emulator running or a physical device connected.

## Instructions

Open the files in the `lib/` directory and locate the `TODO` comments. You need to:

1. **Data Model**: Complete the `BookDetails` class in `book.dart` with `title` and `author` properties and a constructor.
2. **Book Data**: In `main.dart`, create at least four `BookDetails` objects and add them to the `books` list.
3. **Custom Widget**: Complete the `BookCard` widget in `book_card.dart`.
4. **Widget Data**: Make `BookCard` receive a `BookDetails` object through its constructor.
5. **User Interface**: Use a `Card`, `Padding`, and `Column` to display the book title and author.
6. **Styling**: Add suitable text styling and spacing to make each book card clear and readable.

## Expected Output

When completed, the app should display four book cards. Each card should show the book title and author.

The application should demonstrate the following flow:

`BookDetails → List of Books → BookCard → Book Information`
