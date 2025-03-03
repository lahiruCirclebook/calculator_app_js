# Calculator Web App

A simple calculator web application built with **HTML, CSS, and JavaScript**. It supports basic arithmetic operations and provides a user-friendly interface.

## 🚀 Features
- Perform basic arithmetic operations: **Addition (+), Subtraction (-), Multiplication (*), and Division (÷)**
- Clear screen (AC button) and delete last entry (DEL button)
- Supports decimal numbers
- Responsive and visually appealing design

## 🖥️ Live Demo
[Click here to see the live demo](#) (If hosted online)

## 📂 Project Structure
```
📦 Calculator Project
├── 📄 index.html       # HTML structure
├── 📄 styles.css       # Styling (CSS)
├── 📄 script.js        # JavaScript logic
└── 📄 README.md        # Project documentation
```



## ⚙️ How It Works
- Click the number buttons to enter values.
- Use the operation buttons (`+`, `-`, `*`, `÷`) to select an arithmetic operation.
- Press `=` to compute the result.
- Use `AC` to clear the calculator and `DEL` to delete the last digit.

## 📜 Code Overview
### JavaScript Functionality
The `Calculator` class in `script.js` handles the logic:
- `appendNumber(number)`: Appends digits to the current operand.
- `chooseOperation(operation)`: Stores the selected operation and prepares for the next number.
- `compute()`: Performs the arithmetic calculation.
- `updateDisplay()`: Updates the calculator screen.
- `clear()`: Resets the calculator.
- `delete()`: Removes the last entered digit.



