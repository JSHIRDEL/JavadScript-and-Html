## README

### Introduction

This project contains a simple HTML file with embedded JavaScript code. The purpose of the code is to display a list of students and their grades, as well as perform some basic operations on this list.

### File Structure

- **HTML file**: `JavaScript_code.html`
    - Contains HTML structure and embedded JavaScript.

### HTML Structure

The HTML file consists of the following parts:

1. **Head Section**:
    - `<meta charset="UTF-8">`: Specifies the character encoding for the HTML document.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures the webpage is responsive and sets the viewport to match the device's width.
    - `<title>Document</title>`: Sets the title of the webpage.

2. **Body Section**:
    - `<h2>List of Student</h2>`: A heading for the student list.
    - `<p id="list"></p>`: A paragraph element with an ID of "list" where the student list will be displayed.

### JavaScript Functionality

The JavaScript code performs the following tasks:

1. **Student Array**:
    - An array named `Student` contains objects with student names and their respective grades.

2. **Console Output**:
    - Logs the names of students with grades greater than or equal to 17.
    - Logs the names of students with grades less than 12.
    - Logs the names of students whose names start with the letter 'a' (case-insensitive).

3. **Display Student List**:
    - Constructs a string containing the names and grades of all students.
    - Inserts this string into the inner HTML of the paragraph element with the ID "list".


### How to Run

1. Open the `JavaScript_code.html` file in a web browser.
2. The list of students and their grades will be displayed on the webpage.
3. Open the browser's developer console to view the logged information about students.

### Additional Notes

- The JavaScript code uses `console.log` to output information to the console. Make sure to open the developer tools in your browser to see these logs.
- The displayed student list includes all students with their names and grades formatted as `name: [name] ; grade: [grade]`.

---