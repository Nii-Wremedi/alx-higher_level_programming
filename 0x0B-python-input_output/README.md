# README

This repository contains Python scripts that deal with file input/output operations and JSON serialization/deserialization. Below is a description of each script along with its functionality.

## Requirements

- Python Scripts
  - Allowed editors: vi, vim, emacs
  - All files should be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.8.5
  - All files should end with a new line
  - The first line of all files should be exactly `#!/usr/bin/python3`
  - Your code should use the pycodestyle (version 2.8.*)
  - All files must be executable
- Python Test Cases
  - All test files should be inside a folder `tests`
  - All test files should be text files (extension: .txt)
  - All tests should be executed by using the command: `python3 -m doctest ./tests/*`
  - All modules, classes, and functions should have documentation
  - A documentation is not a simple word; it's a real sentence explaining the purpose of the module, class, or method.

## Scripts

1. **Read file**
   - Filename: `0-read_file.py`
   - Function: `def read_file(filename="")`
   - Description: Reads a text file (UTF8) and prints it to stdout.

2. **Write to a file**
   - Filename: `1-write_file.py`
   - Function: `def write_file(filename="", text="")`
   - Description: Writes a string to a text file (UTF8) and returns the number of characters written.

3. **Append to a file**
   - Filename: `2-append_write.py`
   - Function: `def append_write(filename="", text="")`
   - Description: Appends a string at the end of a text file (UTF8) and returns the number of characters added.

4. **To JSON string**
   - Filename: `3-to_json_string.py`
   - Function: `def to_json_string(my_obj)`
   - Description: Returns the JSON representation of an object (string).

5. **From JSON string to Object**
   - Filename: `4-from_json_string.py`
   - Function: `def from_json_string(my_str)`
   - Description: Returns an object (Python data structure) represented by a JSON string.

6. **Save Object to a file**
   - Filename: `5-save_to_json_file.py`
   - Function: `def save_to_json_file(my_obj, filename)`
   - Description: Writes an Object to a text file, using a JSON representation.

7. **Create object from a JSON file**
   - Filename: `6-load_from_json_file.py`
   - Function: `def load_from_json_file(filename)`
   - Description: Creates an Object from a JSON file.

8. **Load, add, save**
   - Filename: `7-add_item.py`
   - Description: Adds all arguments to a Python list, then saves them to a file in JSON format.

9. **Class to JSON**
   - Filename: `8-class_to_json.py`
   - Function: `def class_to_json(obj)`
   - Description: Returns the dictionary description with a simple data structure for JSON serialization of an object.

10. **Student to JSON**
    - Filename: `9-student.py`
    - Description: Defines a student class with instance attributes and a method to retrieve a dictionary representation of a Student instance.

11. **Student to JSON with filter**
    - Filename: `10-student.py`
    - Description: Defines a student class with instance attributes and a method to retrieve a filtered dictionary representation of a Student instance.

12. **Student to disk and reload**
    - Filename: `11-student.py`
    - Description: Defines a student class with instance attributes and methods to retrieve a dictionary representation of a Student instance, and reload attributes from a JSON file.

13. **Pascal's Triangle**
    - Filename: `12-pascal_triangle.py`
    - Function: `def pascal_triangle(n)`
    - Description: Returns a list of lists of integers representing Pascal’s triangle of `n`.

14. **Search and update**
    - Filename: `100-append_after.py`
    - Function: `def append_after(filename="", search_string="", new_string="")`
    - Description: Inserts a line of text to a file after each line containing a specific string.

15. **Log parsing**
    - Filename: `101-stats.py`
    - Description: Reads stdin line by line and computes metrics, printing statistics every 10 lines or after a keyboard interruption.

## Usage

To execute any of these scripts, you can run them directly using Python, for example:

```bash
python3 0-read_file.py
```

For scripts that take command-line arguments, provide the necessary arguments when executing them.

## Testing

To run tests for these scripts, ensure you have the necessary test cases in the `tests` folder and execute them using doctest, for example:

```bash
python3 -m doctest ./tests/*
```

## Contributions

Contributions

 to enhance the functionality, optimize the code, or add more scripts are welcome. Please follow the requirements and guidelines mentioned above when contributing.
