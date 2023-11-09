# Week-2-python
control flow
Control flow in Python refers to the order in which statements are executed in a script or program. Python provides several control flow statements that allow you to modify the flow of execution based on certain conditions, loops, and function calls. Here are the main control flow constructs in Python:

Conditional Statements
if Statement

**Loops**
for Loop
while Loop

Break and Continue Statements
break Statement
Exception Handling
try, except, else, and finally Blocks

Input in Python
To take input from the user, you can use the input() function. It reads a line from the input and returns it as a string (excluding the trailing newline character). You can optionally provide a string argument to display a prompt to the user.
Output in Python:
Python provides several ways to display output
print() Function:
The print() function is used to display output to the console. You can pass one or more comma-separated values to print(), and it will concatenate them into a string and display the result.
Formatting Strings:
You can use formatted strings to format the output using the % operator or the format() method.
f-Strings (Python 3.6 and above):
f-Strings provide a concise and convenient way to embed expressions inside string literals.
File Input and Output:
You can read from and write to files using the built-in open() function and various file methods.

Reading into a textfile
Reading and writing files in Python is a common task that allows you to work with external data. Python provides built-in functions to open, read, write, and close files. Here's how you can perform file input and output operations in Python:

Reading Files:
To read the contents of a file, you can use the open() function with the mode 'r' (read). It returns a file object that you can use to read the file's content.
Reading Lines from a File:
You can also read the file line by line using a loop or the readline() method:
Use a loop ,use readline method

Writing Files:
To write data to a file, you can use the open() function with the mode 'w' (write). If the file doesn't exist, it will be created. If it already exists, its previous content will be erased.
Appending to a File:
To add content to an existing file without erasing its previous content, you can use the mode 'a' (append).
Reading and Writing Binary Files:
To work with binary files, you can use modes 'rb' (read binary) and 'wb' (write binary) instead of 'r' and 'w'.

The random module in Python provides functions for generating random numbers. These functions are often used in applications like simulations, games, and cryptography, where unpredictable or random data is required. Here are some commonly used functions from the random module
Generating Random Float:
The random() function returns a random floating-point number in the range [0.0, 1.0).
Generating Random Integer:
The randint(a, b) function returns a random integer between a and b (inclusive).
Choosing a Random Element from a Sequence:
The choice(seq) function returns a random element from the given sequence (list, tuple, or string).
Shuffling a List:
The shuffle(seq) function shuffles the elements of the given sequence (list) randomly.
Generating Random Float within a Range:
The uniform(a, b) function returns a random floating-point number between a and b.
 Generating Random Choices from a Sequence:
The choices(seq, k) function returns a list with k random elements from the given sequence seq.
Setting the Random Seed:
You can set the initial seed value for the random number generator using the seed(seed) function. This is useful when you want reproducible results.

A recursive function
A recursive function in programming is a function that calls itself in order to solve a problem. Recursive functions are used to break down a problem into smaller, more manageable subproblems. Each recursive call solves a smaller subproblem until a base case is reached, at which point the function stops calling itself and starts returning values back through the chain of recursive calls, ultimately solving the original problem.
Base case(s): These are the terminating conditions that stop the recursion. When the base case is met, the function stops calling itself and starts returning values back up the call stack.
Recursive case(s): This is where the function calls itself with modified parameters. The recursive calls break down the problem into smaller subproblems.
Modified parameters: The parameters passed to the recursive function are typically modified in some way to address a smaller subproblem. This modification ensures progress toward the base case

introduction to data types
Integers
Booleans
Floating point numbers
Complex numbers
Strings

Literals are values that never change, they are not assigned to a variable, and therefore are literal values

Integers	 These represent numbers in an unlimited range. This is only limited by a machine’s memory.
 Booleans	 Evaluate to ‘True or False’, 1 or 0 respectively.
 Floating point numbers	 Floating-point numbers represent double-precision numbers.
 Complex numbers	 Complex numbers represent numbers as a pair of double-precision numbers.
 Strings	 A sequence of Unicode characters e.g. a word or a sentence that can be manipulated.

python integers
In Python, integers are a data type used to represent whole numbers. They can be positive or negative, and they do not have decimal or fractional parts. In Python, you can perform various operations with integers, such as addition, subtraction, multiplication, division, and more.
in python you can add integers in a print statement but cant add integers with string without converting them first. a comma in python print statement means a space or another character will displayed into the print statement.
