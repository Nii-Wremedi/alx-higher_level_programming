Project Title: 0x00. Python - Hello, World
Overview
This project serves as an introduction to Python programming, focusing on fundamental concepts and practices. The tasks involve writing Python scripts to perform various actions, creating shell scripts, and understanding Python's style guide (PEP8). The project covers topics such as printing, string manipulation, and basic programming concepts in Python.

Concepts
The primary concept for this project is Python programming. You will learn and demonstrate your understanding of Python basics, including printing, string manipulation, and adhering to the PEP8 style guide.

Author's Disclaimer
Welcome to the Python world! The initial projects are straightforward and "C-oriented" without complex syntax. Embrace the simplicity of Python and explore its versatility. You'll soon discover multiple ways to approach tasks. Follow the PEP8 style guide, similar to Betty in C.

Enjoy coding in Python!

- Guillaume

Resources
Read or watch the following to enhance your understanding:

The Python tutorial (first three chapters)
Whetting Your Appetite
Using the Python Interpreter
An Informal Introduction to Python (up to "3.1.2. Strings")
How To Use String Formatters in Python 3
Learn to Program
Pycodestyle – Style Guide for Python Code
Learning Objectives
By the end of this project, you are expected to:

Explain why Python programming is awesome
Identify the creator of Python (Guido van Rossum)
Understand the origin of the name 'Python'
Know the Zen of Python
Use the Python interpreter effectively
Print text and variables using print
Work with strings, indexing, and slicing in Python
Follow the official Python coding style (PEP8)
Check code with pycodestyle
Copyright - Plagiarism
Ensure original solutions for the tasks. No plagiarism is allowed, and any form of it will result in removal from the program.

Requirements
Python Scripts
Use editors: vi, vim, emacs
Interpret/compile on Ubuntu 20.04 LTS using python3 (version 3.8.5)
Files should end with a new line
First line of all files: #!/usr/bin/python3
Include a README.md at the root with a description of the repository
Code should use pycodestyle (version 2.8.*)
All files must be executable
Length of files will be tested using wc
Shell Scripts
Use editors: vi, vim, emacs
Test scripts on Ubuntu 20.04 LTS
Scripts should be exactly two lines long (wc -l file should print 2)
Files should end with a new line
First line of all files: #!/bin/bash
All files must be executable
C Scripts
Use editors: vi, vim, emacs
Compile on Ubuntu 20.04 LTS using gcc with specific options
Files should end with a new line
Code should use the Betty style
No more than 5 functions per file
Prototypes of functions should be included in a header file (lists.h)
Don't forget to push your header file
All header files should be include guarded
Zen
The Zen of Python, by Tim Peters, outlines key principles of Python programming. Embrace these principles in your code.

Pycodestyle
Pycodestyle is the new standard of Python style code. Adhere to its guidelines for clean and readable code.

Tasks
Run Python file

Write a Shell script (0-run) that runs a Python script.
The Python file name will be saved in the environment variable $PYFILE.
Run inline

Write a Shell script (1-run_inline) that runs Python code.
The Python code will be saved in the environment variable $PYCODE.
Hello, print

Write a Python script (2-print.py) that prints "Programming is like building a multilingual puzzle" followed by a new line.
Print integer

Complete a Python script (3-print_number.py) to print an integer stored in the variable number followed by "Battery street" and a new line.
Do not cast number into a string, use f-strings.
Print float

Complete a Python script (4-print_float.py) to print the float stored in the variable number with a precision of 2 digits.
Print string

Complete a Python script (5-print_string.py) to print a string stored in the variable str three times, followed by its first 9 characters.
Play with strings

Complete a Python script (6-concat.py) to print "Welcome to Holberton School!" without using any loops or conditional statements.
Copy - Cut - Paste

Complete a Python script (7-edges.py) to manipulate the string word and print its first 3 letters, last 2 letters, and the middle word.
Create a new sentence

Complete a Python script (8-concat_edges.py) to print "object-oriented programming with Python" without using any loops or conditional statements.
Easter Egg

Write a Python script (9-easter_egg.py) that prints "The Zen of Python" by Tim Peters.
Linked list cycle

Write a C function (10-check_cycle.c) to check if a singly linked list has a cycle.
Return 0 if there is no cycle, 1 if there is a cycle.
Hello, write

Write a Python script (100-write.py) to print "and that piece of art is useful - Dora Korpar, 2015-10-19" to stderr.
The script should exit with a status code of 1.
Compile

Write a script (101-compile) to compile a Python script file.
The Python file name will be stored in the environment variable $PYFILE.
The output filename will be $PYFILEc.
ByteCode -> Python #1

Write a Python function (102-magic_calculation.py) that performs the same as given Python bytecode.
Conclusion
This project aims to build a solid foundation in Python programming, emphasizing good coding practices and adherence to style guidelines.
