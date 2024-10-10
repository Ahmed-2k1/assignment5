# Python Calculator Application with Plugin Architecture

This project is a Python-based calculator application that leverages a plugin-based architecture to perform various arithmetic operations. Users can carry out mathematical operations such as addition, subtraction, multiplication, and division. Each operation is implemented as a standalone plugin, and the application supports the dynamic loading of these plugins during runtime.

## Key Features

- **Dynamic Plugin Loading**: Arithmetic operations (addition, subtraction, multiplication, division) are dynamically loaded as plugins.
- **Command Pattern**: Implements a structured command pattern to manage operations efficiently.
- **Interactive CLI Menu**: Users can interact with the application via a command-line menu that offers available operations.
- **Error Handling**: Includes comprehensive error handling to manage invalid inputs such as division by zero or non-numeric entries.

## Installation

To set up the project dependencies, use the following command:

```bash
pip install -r requirements.txt
```
## Running Tests
To execute tests and ensure code quality, run the following commands:
pytest
pytest --pylint
pytest --cov

## Running the Application
To launch the application, use this command:
python3 main.py
