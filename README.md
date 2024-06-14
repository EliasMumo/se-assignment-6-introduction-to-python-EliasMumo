[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15275643&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Answer:
   Python is a high-level, interpreted programming language known for its simplicity and readability.SOme fo it's key features are simple and easy to learn, rich standart library, multiple third party library,versatile-cross platform.Python is widely used in various fields, including web development, data science, artificial intelligence, scientific computing, and more. 

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Answer:
   FIrst Open your browser type in the search bar python.org.Once on the website locate the download tab and click it then click download python<version>.Once installed go to the download and run the installer and install python to your pc.Once that is done locate the python version installed and copy it's path.Add the copied path to the system and environment variables so that the machine is able to use it.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   Answer:
     # Print statement
   print("Hello, World!")


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Answer:
   integers:Represents positive or negative whole numbers without any decimal point.
   float:Represents real numbers (numbers with decimal points).
   boolean:epresents truth values True or False
   string:Represents sequences of characters enclosed within quotes (single or double).
   list:Represents ordered collections of items, which can be of different data types.
   tuple:Represents ordered collections of items, similar to lists, but tuples are immutable (cannot be changed).

  Variables:
  integer_var = 10
  float_var = 3.14
  boolean_var = True
  string_var = "Hello, Python!"
  list_var = [1, 2, 3, 4, 5]
  tuple_var = (10, 20)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Answer:
   Conditional statements and loops  allow you to control the flow of execution based on conditions and to repeat operations multiple times.

   If-else stamtement:
   x = 10

if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")

    for loop:
    fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Answer:
    Functions in Python are blocks of reusable code that perform a specific task. They provide a way to organize code into logical units, making it easier to manage and reuse.
    Example:
    def add_numbers(a, b):
    """
    Function to add two numbers.
    
    Parameters:
    a (int or float): First number.
    b (int or float): Second number.
    
    Returns:
    int or float: Sum of a and b.
    """
    return a + b

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

    Answer:
    DIFERRENCES:
     Lists maintain the order of elements and access items by their index.While dictionaries do not maintain the order of elements and access items by keys.
Lists are mutable; you can add, remove, or change elements after creation.While dictionaries are mutable; you can add, remove, or change key-value pairs after creation.
Lists can contain elements of different data types, and duplicate values are allowed.While dictionaries store data as key-value pairs, where each key is unique.
Elements in a list are accessed using integer indices, e.g., my_list[0].While elements in a dictionary are accessed using keys, e.g., my_dict['key'].
Lists are defined using square brackets, e.g., my_list = [1, 2, 3].While dictionaries are defined using curly braces and colons, e.g., my_dict = {'key': 'value'}

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   
   Answer:
   Exception handling in Python is a mechanism that allows you to manage and respond to errors and exceptions that occur during the execution of your program. It helps in preventing your program from crashing when an error occurs and provides the ability to handle the error gracefully.

   Example:
   ef divide_numbers(x, y):
    try:
        result = x / y
    except ZeroDivisionError:
        print("Error: Division by zero!")
        result = None
     except TypeError as e:
        print(f"Error: {e}")
        result = None
     except Exception as e:
        print(f"Unexpected error occurred: {e}")
        result = None
     finally:
        print("Executing finally block")
        # Clean-up code (e.g., closing files or releasing resources)

    return result

    # Test cases
    print(divide_numbers(10, 2))    # Output: 5.0
    print(divide_numbers(10, 0))    # Output: Error: Division by zero! \n Executing finally block \







9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example  using the `math` module.

    Answer:
    Modules in Python are files containing Python definitions and statements. They can define functions, classes, and variables that you can use in other Python scripts or interactive sessions.
    Packages in Python are a way of structuring Python's module namespace by using "dotted module names". A package can contain multiple  modules and sub-packages.

    Example:
    import math

    # Using functions from the math module
   print("Value of pi:", math.pi)                
    print("Square root of 16:", math.sqrt(16))     
    print("Factorial of 5:", math.factorial(5))     
    print("Sine of 0.5 radians:", math.sin(0.5))   

# Using constants from the math module
    radius = 5
   area = math.pi * radius ** 2
    print("Area of a circle with radius 5:", area)  # Output: Area of a circle with radius 5: 78.53981633974483

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    Answer:
    Reading:
    To read from a file in Python, you can use the built-in open() function to open a file and then use various methods like read(), readline(), or readlines() to read the content. Here's an 
    Writing:
    To write to a file in Python, you can use the open() function with 'w' mode to open the file for writing.

    Example(Reads content and prints):
    file_path = 'sample.txt'
with open(file_path, 'r') as file:
    # Read and print the entire content
    content = file.read()
    print(content)

    Example:(writes list of strings to  a file):
    lines = [
    "Python is awesome!\n",
    "Writing to files is easy.\n",
    "You can write any text you like.\n"
]

# Open the file in write mode
    output_file = 'output.txt'
    with open(output_file, 'w') as file:
       # Write each string in the list to the file
        file.writelines(lines)

    print(f"Successfully wrote {len(lines)} lines to '{output_file}'")



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


