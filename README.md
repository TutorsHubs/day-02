# day-02

Welcome to the Day Two Tutors module! This module covers creating forms and tables and how to effectively use them in your web development projects.

## Features 🌈

- ✨ Accessibility in VS Code
- 🌟 Download directly to project root
- 💡 Live Previews

## Screenshots

![App Screenshot](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210910153459/1230.png)

## Table of Contents

1. [Introduction](#introduction)
2. [Working with Forms](#working-with-forms)
    1. [Forms](#forms)
    2. [Forms](#forms-1)
3.[working with tables](#Tables)

## Introduction

The Day Two Tutors module is designed to teach you the essentials of creating forms and tables in web development. By the end of this module, you will have a solid understanding of how to use these elements effectively.



Contributing 🤝
Contributions are welcome! Please follow these guidelines:

Fork the repository.
Create a new branch: git checkout -b feature/your-feature.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature/your-feature.
Submit a pull request.
License 📄
This project is licensed under the License Name - see the LICENSE file for details.

Feel free to reach out to me if you have any questions or suggestions. Happy coding! 😄

Certainly! Let's delve deeper into tables and forms in HTML for beginners.

## Tables in HTML 📊

### What is a Table?

- A table is an HTML element used to organize and display data in a structured grid format. It's a fundamental component for presenting information in rows and columns.

### Basic Table Structure:

- `<table>`: This tag defines the container for the entire table.
- `<tr>`: Represents a table row. You include these within the `<table>` element.
- `<th>`: Defines a table header cell. Typically found in the first row (`<tr>`) and used to label columns.
- `<td>`: Represents a table data cell. Contains the actual data.

Example:

```html
<!DOCTYPE html>
<html>
 
<body>
    <table>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
            <th>Age</th>
        </tr>
        <tr>
            <td>Priya</td>
            <td>Sharma</td>
            <td>24</td>
        </tr>
        <tr>
            <td>Arun</td>
            <td>Singh</td>
            <td>32</td>
        </tr>
        <tr>
            <td>Sam</td>
            <td>Watson</td>
            <td>41</td>
        </tr>
    </table>
</body>
 
</html>
```
## Screenshots

![App Screenshot](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210910153459/1230.png)



### Table Attributes:

- `border`: Specifies the width of the table border. Common values are `0` for no border and `1` for a thin border.
- `cellpadding`: Defines the space between the content of a cell and the cell border.
- `cellspacing`: Sets the space between cells.

Example:

```html
<table border="1" cellpadding="5" cellspacing="10">
  <!-- Table content -->
</table>
```

### Table Accessibility:

- Use `scope` and `headers` attributes to make tables more accessible for screen readers. This helps associate data cells with their respective header cells.

Example:

```html
<table>
  <tr>
    <th id="header1">Header 1</th>
    <th id="header2">Header 2</th>
  </tr>
  <tr>
    <td headers="header1">Data 1</td>
    <td headers="header2">Data 2</td>
  </tr>
</table>
```

## Forms in HTML 📝

### What is a Form?

- A form is an HTML element used to collect and submit user input. Forms are crucial for various interactive features like login, registration, search, and data submission.

### Basic Form Structure:

- `<form>`: This tag defines the container for the entire form. It wraps all form elements.
- `<input>`: The most common element for various types of user input, such as text, checkboxes, radio buttons, and more.
- `<textarea>`: Used for multiline text input.
- `<select>`: Creates dropdown menus.
- `<button>`: Provides buttons for submitting or resetting the form.

Example:

```html
<form>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required>

  <button type="submit">Submit</button>
</form>
```

### Form Attributes:

- `action`: Specifies the URL where the form data is sent when submitted.
- `method`: Defines the HTTP method used for sending data (usually `GET` or `POST`).
- `name`: Gives the form a unique identifier, useful when dealing with multiple forms on a page.

Example:

```html
<form action="submit.php" method="POST" name="loginForm">
  <!-- Form content -->
</form>
```

### Form Validation:

- HTML5 introduced built-in validation attributes like `required`, `min`, `max`, and `pattern` for input elements to ensure data correctness.
- Additionally, JavaScript can be used for custom validation and enhancing user experience.

### Styling Forms:

- Use CSS to style form elements, making them visually appealing and consistent with your website's design.

```css
/* Example CSS to style form elements */
input[type="text"],
input[type="password"],
button {
  /* Your styles here */
}
```

## Conclusion

Tables and forms are foundational elements in HTML, allowing you to structure and interact with data on your web pages. Mastering these concepts is crucial for creating well-organized, user-friendly websites and web applications.
