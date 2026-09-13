# fundamental_Lab1
Fundamental of python 
# Python Fundamentals – Lab 1

This repository contains my practice work for **Python Fundamentals – Lab 1**.

The goal of this lab is to build a strong foundation in Python by practising variables, data types, operators, user input, type conversion, and basic string operations.

## Topics Covered

### Hello World and `print()`

Practised displaying information using Python's `print()` function.

```python
print("Hello, World!")
print("Learning Python")
```

## Comments

Practised adding comments to make code easier to understand.

```python
# This is a Python comment
print("Hello, World!")
```

## Variables

Practised creating and using variables.

```python
name = "Mohana"
age = 30
height = 165.5
student = True
```

Python variables can also change their data type.

```python
value = 100
print(type(value))

value = "one hundred"
print(type(value))
```

## Variable Naming

Practised different naming styles:

```python
# Camel Case
myVariableName = "John"

# Pascal Case
MyVariableName = "John"

# Snake Case
my_variable_name = "John"
```

For Python variables, **snake_case** is generally the preferred naming convention.

## Python Data Types

Practised basic Python data types:

```python
name = "Mohana"      # str
age = 30             # int
height = 165.5       # float
student = True       # bool
```

Checked types using:

```python
print(type(name))
print(type(age))
print(type(height))
print(type(student))
```

## Arithmetic Operators

Practised the main arithmetic operators:

```python
print(10 + 5)   # Addition
print(10 - 5)   # Subtraction
print(10 * 5)   # Multiplication
print(10 / 5)   # Division
print(10 // 3)  # Floor division
print(10 % 3)   # Modulus / remainder
print(10 ** 2)  # Exponentiation
```

Important operators learned:

| Operator | Meaning        |
| -------- | -------------- |
| `+`      | Addition       |
| `-`      | Subtraction    |
| `*`      | Multiplication |
| `/`      | Division       |
| `//`     | Floor division |
| `%`      | Remainder      |
| `**`     | Exponent       |

## Type Conversion

Practised converting values between different data types.

### String to Integer

```python
age = "30"
age = int(age)

print(type(age))
```

### Integer to Float

```python
number = 5
number = float(number)

print(number)
```

### Number to String

```python
number = 5
text = str(number)

print(text)
```

## User Input

Practised collecting information from the user with `input()`.

```python
name = input("What is your name? ")

print(name)
```

Because `input()` returns a string, numeric inputs may need conversion:

```python
birth_year = int(input("What is your birth year? "))
```

## Age Calculator

Created a simple program that calculates approximate age from the birth year.

```python
current_year = 2026

name = input("What is your name? ")
birth_year = int(input("What is your birth year? "))

age = current_year - birth_year

print(name, "is approximately", age, "years old.")
```

## Discount Calculator

Created a basic discount calculator using user input and arithmetic.

```python
price = float(input("Enter price: "))
discount = float(input("Enter discount percentage: "))

discount_amount = price * discount / 100
final_price = price - discount_amount

print("Final price:", round(final_price, 2))
```

This exercise helped me combine:

* Variables
* User input
* Type conversion
* Arithmetic
* `round()`

## F-Strings

Practised formatting strings using f-strings.

```python
first_name = input("First name: ")
last_name = input("Last name: ")

full_name = f"{first_name} {last_name}"

print(full_name)
```

## String Methods

Practised common string methods:

```python
text = "  Hello World  "

print(len(text))
print(text.upper())
print(text.lower())
print(text.strip())
print(text.replace("World", "Python"))
print(text.split())
```

Important methods learned:

```python
.upper()
.lower()
.strip()
.replace()
.split()
.find()
```

## String Indexing

Practised accessing individual characters.

```python
word = "Python"

print(word[0])   # P
print(word[-1])  # n
```

## String Slicing

Practised extracting parts of strings.

```python
word = "Python"

print(word[:3])
print(word[1:])
```

## Username Generator

Practised combining slicing with string methods.

```python
first_name = input("First name: ").strip().lower()
last_name = input("Last name: ").strip().lower()

username = first_name[:3] + last_name[:5]

print("Username:", username)
```

## Email Parsing

Practised finding characters and extracting parts of a string.

```python
email = "sam@gmail.com"

at_position = email.find("@")

username = email[:at_position]
domain = email[at_position + 1:]

print(username)
print(domain)
```

This exercise introduced basic text parsing.

## String Immutability

Practised understanding that Python strings cannot be changed directly.

```python
word = "Python"

new_word = "S" + word[1:]

print(new_word)
```

## File

`fund-class1.ipynb`

The Jupyter Notebook contains my Python Fundamentals Lab 1 exercises and practice code.

## Learning Outcomes

After completing this lab, I have practised:

* Writing basic Python programs
* Using variables and data types
* Checking types with `type()`
* Performing arithmetic calculations
* Understanding `/`, `//`, `%`, and `**`
* Converting between strings, integers, and floats
* Accepting user input
* Formatting output
* Working with strings
* Using indexing and slicing
* Applying common string methods
* Building small programs from multiple Python concepts

## Technologies

* Python
* Jupyter Notebook
* Git
* GitHub

## Next Step

The next stage is **Python Fundamentals – Lab 2**, where I practise Python collections such as:

* Lists
* Tuples
* Sets
* Dictionaries
* Nested collections

## Author

**Mohana**

Learning Python as part of my journey toward **System Development, Data Analytics, Python and AI**.

