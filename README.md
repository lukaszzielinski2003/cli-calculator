# CLI Calculator

This is a simple Command Line Interface (CLI) calculator written in Python.
It supports basic arithmetic operations: addition, subtraction, multiplication, division, and exponentiation.

## About this project

This is my first project created with the help of educational tools like ChatGPT.
Through building this CLI calculator, I learned how to:

- Structure a Python project with modules and packages.
- Implement basic OOP concepts (like the Calculator class).
- Handle user input and exceptions gracefully.
- Write and run unit tests using pytest.
- Use code style tools such as flake8 and black to maintain clean code.

This experience has helped me improve my Python skills and gave me confidence to build more complex projects in the future.

## Features

- Add, subtract, multiply, divide, and power operations.
- Handles division by zero and invalid inputs gracefully.
- User-friendly CLI menu.
- Clean and modular code structure.
- Code style checked with [flake8](https://flake8.pycqa.org/en/latest/) and formatted by [black](https://black.readthedocs.io/en/stable/).
- Unit tests included using [pytest](https://docs.pytest.org/en/stable/).

## Setup

To install all required tools for testing and code formatting, run:

```bash
pip install -r requirements.txt
```

## How to Run

1. Make sure you have Python 3 installed.
2. Clone this repository:

   ```bash
   git clone https://github.com/lukaszzielinski2003/cli-calculator
   ```

3. Navigate to the project folder:

   ```bash
   cd cli_calculator
   ```

4. Run the program:

   ```bash
   python main.py
   ```

## Development

1. To check code style with flake8:

   ```bash
   flake8 cli_calculator
   ```

2. To automatically format code with black:

   ```bash
   black cli_calculator
   ```

3. To run tests with pytest:

   ```bash
   pytest tests
   ```

## Usage

- Choose an operation from the menu by entering a number (1-6).
- Enter two numbers when prompted.
- See the result displayed.
- To exit, choose option 6 or press Ctrl+C.

## Sample

```
==================
| CLI CALCULATOR |
==================
| 1. Add         |
| 2. Subtract    |
| 3. Multiply    |
| 4. Divide      |
| 5. Power       |
| 6. Exit        |
==================
Select operation: 1
Enter the first number: 10
Enter the second number: 10
Result: 20.0
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

### Made by Łukasz Zieliński
