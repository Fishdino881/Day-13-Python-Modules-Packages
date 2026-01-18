# Day 13-Python-Modules-Packages

Overview

Modules and packages in Python help organize code into reusable, maintainable components. A module is a Python file containing functions, classes, and variables, while a package is a collection of modules in a directory structure.

Using modules allows you to import functions and variables from other files:

```python
# main.py
import example

result = example.pi
result = example.square(3)
result = example.cube(3)
result = example.circumference(3)
result = example.area(3)

print(result)
```

```python
# example.py
pi = 3.14159

def square(x):
    return x ** 2

def cube(x):
    return x ** 3

def circumference(radius):
    return 2 * pi * radius

def area(radius):
    return pi * radius ** 2
```

---

Python `pip`

`pip` is Python’s package manager, used to install and manage modules and packages from the Python Package Index (PyPI).

Common pip commands:

 Check pip version:

  ```bash
  pip --version
  ```
 Update pip:

  ```bash
  pip install --upgrade pip
  ```
 List installed packages:

  ```bash
  pip list
  ```
 List outdated packages:

  ```bash
  pip list --outdated
  ```
 Install or upgrade a package:

  ```bash
  pip install "package_name"
  pip install "package_name" --upgrade
  ```

Modules and packages streamline your Python workflow by reusing code and managing dependencies efficiently.
