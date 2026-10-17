This a Simple Calculator

# Smart Spelling-Aware Calculator

A simple, user-friendly Python command-line calculator that performs basic arithmetic operations. The script features robust input parsing and automatic spelling correction for operation commands.

## Features

- Basic Arithmetic: Supports Addition (+), Subtraction (-), Multiplication (*), and Division (/).
- Spelling Auto-Correction: Uses fuzzy matching to recognize typed words (e.g., "subtrcat" -> "subtract") and special keywords like "handle".
- Crash Protection: Built-in validation to prevent ZeroDivisionError crashes when dividing by zero.
- Flexible Formatting: Accepts space-separated float values for clean input.

---

## How to Run

### Prerequisites
Make sure you have Python 3.x installed on your system. This script relies entirely on standard built-in libraries (difflib), so no external package installations are required.

### Execution Steps
1. Download or copy the script code into a file named calculator.py.
2. Open your terminal or command prompt.
3. Navigate to the directory containing the file.
4. Run the script using the following command:
   python calculator.py

---

## Usage Examples

### Standard Math Symbols
Enter two values separated by a space (e.g., 1 3): 10 5
Enter an Operation (or type 'handle'): *
Product Of 10.0 * 5.0 is :  50.0
Good Bye!

### Typo / Spelling Handling
Enter two values separated by a space (e.g., 1 3): 12 4
Enter an Operation (or type 'handle'): divede
Quotient Of 12.0 / 4.0 is :  3.0
Good Bye!

### The "Handle" Trigger
Enter two values separated by a space (e.g., 1 3): 5 5
Enter an Operation (or type 'handle'): hnadle
Spelling handled! You entered 'hnadle', which I recognized as 'handle'.
Defaulting to addition: 5.0 + 5.0 = 10.0
Good Bye!

---

## License
This project is open-source and free to use or modify.
