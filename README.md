# 🧮 Calculix

> A lightweight desktop calculator built with Python and Tkinter.

**Calculix** is a simple graphical calculator application developed using **Python** and **Tkinter**. It provides a clean, beginner-friendly interface for performing basic arithmetic operations.

This project was created to practice Python GUI development, event handling, functions, and interaction between UI components.

---

## Features

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division
* 🔢 Numeric input from `0–9`
* 🧹 Clear button
* ⚠️ Division-by-zero error handling
* 🖥️ Simple desktop GUI
* 🖱️ Button-based interaction

---

## Technologies Used

* **Python 3**
* **Tkinter** — Python's built-in GUI library

No external packages are required.

---

## Project Structure

```text
Calculix/
│
├── calculator.py
└── README.md
```

---

## Getting Started

### Prerequisites

Make sure **Python 3** is installed on your computer.

You can verify your Python installation with:

```bash
python --version
```

---

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/calculix.git
```

Navigate to the project directory:

```bash
cd calculix
```

---

### Run the Application

Run the following command:

```bash
python calculator.py
```

The Calculix GUI will open in a new window.

---

## How It Works

Calculix uses Tkinter widgets to create the graphical interface.

### `Label`

The display area shows the numbers entered by the user and the calculation result.

### `Button`

Each calculator button triggers a specific function when clicked.

### Functions

The application uses separate functions for different tasks:

* `get_digit()` — handles numeric input
* `get_operator()` — stores the selected arithmetic operator
* `get_result()` — performs the calculation
* `clear()` — clears the calculator display

### Global Variables

The calculator temporarily stores:

* `first_number`
* `second_number`
* `operator`

These values are used to perform the selected calculation.

---

## Supported Operations

| Operation      | Example | Result |
| -------------- | ------- | -----: |
| Addition       | `5 + 3` |    `8` |
| Subtraction    | `5 - 3` |    `2` |
| Multiplication | `5 × 3` |   `15` |
| Division       | `6 ÷ 3` |  `2.0` |

Division by zero is handled with an error message instead of crashing the application.

---

## Preview

*Screenshot of Calculix can be added here.*

```text
Add a screenshot or GIF of the calculator interface here.
```

---

## Future Improvements

The current version focuses on basic calculator functionality. Possible future improvements include:

* [ ] Decimal number support
* [ ] Backspace button
* [ ] Percentage calculations
* [ ] Positive/negative (`+/-`) button
* [ ] Keyboard input support
* [ ] Calculation history
* [ ] Improved error handling
* [ ] Dark/light themes
* [ ] Improved and responsive UI
* [ ] Scientific calculator functions
* [ ] Refactor the project using Object-Oriented Programming (OOP)

---

## Learning Goals

This project helped me practice:

* Python functions
* Variables and data types
* Conditional statements
* Global variables
* Tkinter GUI development
* Tkinter widgets
* `grid()` layout management
* Button commands and event handling
* Lambda functions
* Basic error handling
* Building a small desktop application

---

## Project Status

**Current Status:** 🟢 Working

Calculix currently supports the four basic arithmetic operations and provides a simple graphical interface.

More functionality may be added in future versions as the project evolves.

---

## Author

**Muqaddas Iftikhar**

Built with 🐍 Python and ❤️ while learning GUI development.

---

## 📄 License

This project is available for educational and personal use.
