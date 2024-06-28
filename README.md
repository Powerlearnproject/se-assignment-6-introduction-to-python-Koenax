[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15339931&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   Python is a high-level, interpreted programming language that is widely used in web development, data science, scientific computing, and many other fields. Its simplicity and flexibility make it a popular choice for beginners and experienced programmers alike.Object-oriented: Python is an object-oriented language, which means that it is based on the concept of objects. Objects are data structures that contain both data and methods, which are functions that operate on the data. This allows you to create reusable code that can be easily modified and extended.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   Since Python can be installed on multiple platforms like Windows, Mac, and Linux, it is vital to download the appropriate installer for your specific operating system. Navigate to the official Python download page for Windows to find the latest stable Python 3 release that is suitable for your system. You will find separate links for downloading Python on 64-bit and 32-bit Windows. It is crucial to download the correct installer, as using the wrong version can cause compatibility issues. How to Install Python on Windows?

Download Python Installer
You can install Python on Windows in two ways.
1. Installation from the official installer package.
2. Installation from Microsoft Store.

To install Python on your Windows machine using the installer package, you need to download the official Python installer. Follow these steps:

1. Open your preferred web browser.
2. Navigate to the official Python website at https://www.python.org/.
3. Click on the “Downloads” tab in the menu.
4. On the downloads page, scroll down until you find the latest stable version of Python for Windows.
5. Select the appropriate installer based on your system architecture (32-bit or 64-bit).
6. Click on the installer to begin the download.
7. Wait for the download to complete.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   python program to print "Hello World" 
print("Hello World")


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   A data type in programming defines the type of data that a variable can hold. It determines the operations that can be performed on the data and the way it is stored in memory. Examples in Python include integers (int), floating-point numbers (float), strings (str), lists (list), dictionaries (dict), etc.# Variables are dynamically typed
a = 5  # 'a' is of type int
b = "Hello"  # 'b' is of type str

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   Conditional Statements are statements in Python that provide a choice for the control flow based on a condition. It means that the control flow of the Python program will be decided based on the outcome of the condition.
age = 18

if age >= 18:
    print("You are old enough to vote.")
A loop is a repetitive statement or task.
A for-loop statement in Python is used to iterate over a sequence (such as a list, tuple, or string) and perform a certain action for each item in the sequence.
# Print each character in a string using a for loop
word = "Python"
for letter in word:
    print(letter)

   


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   Functions in Python are useful for running a block containing a Python script that functions to carry out a certain task.
A function is designed to accept or not receive an input, and produce an output or task.
Why can you accept or not receive input, but can produce output? Because the function itself is designed to execute a command and simplify the script, where the command can have a variable input or not.

   # function definition creates a function called "add_numbers" that takes two parameters: "a" and "b".
# It returns the sum of "a" and "b" by using the sum() function on a list containing "a" # and "b".
def add_numbers(a, b):
    return sum([a, b])

# This variable stores the result of calling the "add_numbers" function with 5 and 10 as #arguments.
result = add_numbers(5, 10)

# This line prints the result of the addition.
# The f-string is used to include the "result" in the output.
print(f"The sum is {result}")

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   Lists are ordered Python data structures in which every element can be accessed using an index. Dictionaries are data structures in which each element is a key-value pair. Your choice between lists or dictionaries depends on the requirements you have for your Python application.
example of a list that has three elements of different types (float, string, and integer):
values = [4.5, 'hour', 23]
Dictionaries are collections of key-value pairs. They are unordered, mutable, and iterable. A dictionary is delimited by curly brackets and key-value pairs are separated by commas. Dictionaries are also called hash tables or hashmaps in other programming languages.
Below you can see an example of a Python dictionary:
values = {'user1': 23, 'user2': 456, 'user3': 44}


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   To handle exceptions, you use the try statement. The try statement has the following clauses:
try:
    # code that you want to protect from exceptions
except <ExceptionType> as ex:
    # code that handle the exception
finally:
    # code that always execute whether the exception occurred or not
else:
    # code that excutes if try execute normally (an except clause must be present
The finally clause may appear zero or 1 time in a try statement. The finally clause always executes whether an exception occurred or not.


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   Modular programming refers to the process of breaking a large, unwieldy programming task into separate, smaller, more manageable subtasks or modules. Individual modules can then be cobbled together like building blocks to create a larger application.
If a file named __init__.py is present in a package directory, it is invoked when the package or a module in the package is imported. This can be used for execution of package initialization code, such as initialization of package-level data.
For example, consider the following __init__.py file:
__init__.py


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    write() : Inserts the string str1 in a single line in the text file.



Reading From a File Using read()
read() : Returns the read bytes in form of a string. Reads n bytes, if no n specified, reads the entire file.
File_object.write(str1)
def read_file(file_path):
    try:
        # Open file in read mode
        with open(file_path, 'r') as file:
            # Read the entire content of the file
            content = file.read()
            print(content)
    except FileNotFoundError:
        print(f"Error: The file '{file_path}' does not exist.")

# Example usage
file_path = 'sample.txt'  # Replace with your file path
read_file(file_path)


write() : Inserts the string str1 in a single line in the text file.
Here's a script (write_file.py) that writes a list of strings to a file:
python
Copy code
def write_to_file(file_path, lines):
    try:
        # Open file in write mode
        with open(file_path, 'w') as file:
            # Write each line from the list
            for line in lines:
                file.write(line + '\n')
        print(f"Successfully wrote {len(lines)} lines to '{file_path}'.")
    except IOError:
        print(f"Error writing to file '{file_path}'.")

# Example usage
file_path = 'output.txt'  # Replace with your desired file path
lines_to_write = [
    "Hello,",
    "This is a test file.",
    "Writing some lines to demonstrate file writing in Python."
]
write_to_file(file_path, lines_to_write)
Sources used: python learn, geeksforgeeks, meduim

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


