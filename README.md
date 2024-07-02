[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15359552&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   - Python is a high-level, interpreted programming language known for its simplicity and readability. It is dynamically typed and supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

Key Features:

Readable Syntax: Python's syntax is clear and easy to understand, which reduces the cost of program maintenance.
Dynamically Typed: No need to declare variable types explicitly.
Interpreted: Python code is executed line-by-line, making debugging easier.
Extensive Libraries: Python has a rich standard library and many third-party libraries.
Cross-platform: Python runs on various operating systems, including Windows, macOS, and Linux.
Use Cases:

Web Development: Frameworks like Django and Flask.
Data Analysis: Libraries like Pandas and NumPy.
Machine Learning: Libraries like TensorFlow and scikit-learn.
Scripting: Automating tasks and system administration.
Game Development: Libraries like Pygame

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
On Windows:

Download the installer from the official Python website.
Run the installer and check the box that says "Add Python to PATH".
Click "Install Now".
Verify installation by opening Command Prompt and typing python --version.

On macOS:

Python is usually pre-installed. To check, open Terminal and type python3 --version.
To install or update, you can use Homebrew:
'brew install python'
Verify by typing 'python3 --version'.

On Linux:

Most distributions come with Python pre-installed. Check by typing python3 --version in Terminal.
To install or update:
sudo apt-get update
sudo apt-get install python3
Verify by typing python3 --version.
Setting Up a Virtual Environment:

Create a virtual environment:

'python -m venv myenv'
Activate the environment:
Windows: myenv\Scripts\activate
macOS/Linux: source myenv/bin/activate
Verify the environment is active by checking the Python version with 'python --version'.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   - print("Hello, World!")
Explanation:
print(): A built-in function that outputs text to the console.
"Hello, World!": A string literal enclosed in double quotes.
No semicolons or braces are required; indentation is used to define code blocks

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
Basic Data Types:

Integer (int): Whole numbers, e.g., 5.
Float (float): Decimal numbers, e.g., 5.5.
String (str): Sequence of characters, e.g., "hello".
Boolean (bool): Represents True or False.
Script:
# Integer
a = 10
# Float
b = 20.5
# String
c = "Hello"
# Boolean
d = True
print(a, b, c, d)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
Conditional Statements:
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is 5 or less")

For Loop:
for i in range(5):
    print(i)

Explanation:

if-else: Executes code blocks based on condition.
for loop: Iterates over a sequence or range of numbers.

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
Functions are reusable blocks of code that perform a specific task. They help in organizing and modularizing code.
Example Function:

def add_numbers(a, b):
    return a + b

result = add_numbers(5, 3)
print(result)

Explanation:
def add_numbers(a, b): Defines a function named add_numbers with parameters a and b.
return a + b: Returns the sum of a and b

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
Lists:
Ordered and mutable collections.
Example: [1, 2, 3]

Dictionaries:
Unordered collections of key-value pairs.
Example: {'name': 'Brian', 'age': 25}

# List
numbers = [1, 2, 3, 4, 5]
print("List:", numbers)

# Dictionary
person = {'name': 'Alice', 'age': 30}
print("Dictionary:", person)

Basic Operations:
List: Indexing, appending, iterating.
Dictionary: Accessing values by keys, updating, iterating over items.

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
Exception handling allows a program to deal with runtime errors gracefully without crashing.
Example:
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Execution completed.")
Explanation:
try: Block of code that might throw an exception.
except: Block that handles the exception.
finally: Block that executes regardless of exceptions. 

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
A module is a file containing Python code (e.g., functions, variables) that can be imported and used in other scripts.
A package is a collection of modules organized in directories.
Example Using math Module:
import math

print(math.sqrt(16))  # Outputs: 4.0
Explanation:
import math: Imports the math module.
math.sqrt(): Calls the sqrt function from the math module

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
Reading from a File:
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
Writing to a File:
lines = ['Hello', 'World', 'Python']

with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')
Explanation:
open(filename, mode): Opens a file.
read(): Reads the file content.
write(): Writes data to the file.
with: Ensures the file is properly closed after operations.  

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


