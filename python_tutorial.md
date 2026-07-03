# Python Tutorial for Beginners

Welcome! This guide will walk you through the basics of Python, one of the most beginner-friendly and widely used programming languages in the world. No prior coding experience is required.

## Table of Contents
1. [Getting Started](#getting-started)
2. [Variables and Data Types](#variables-and-data-types)
3. [Basic Operators](#basic-operators)
4. [Strings](#strings)
5. [Lists](#lists)
6. [Conditionals](#conditionals)
7. [Loops](#loops)
8. [Functions](#functions)
9. [Next Steps](#next-steps)

---

## Getting Started

Python is a general-purpose programming language known for its clean, readable syntax. To follow along:

1. Install Python from [python.org](https://www.python.org/downloads/)
2. Verify the install by opening a terminal and running:
   ```bash
   python3 --version
   ```
3. Create a file called `hello.py` and add:
   ```python
   print("Hello, world!")
   ```
4. Run it:
   ```bash
   python3 hello.py
   ```

You should see `Hello, world!` printed to your screen.

---

## Variables and Data Types

Variables store data so you can use it later. Python doesn't require you to declare a type — it figures it out automatically.

```python
name = "Alice"       # string
age = 30              # integer
height = 5.6          # float
is_student = True     # boolean
```

**Common data types:**

| Type | Example | Description |
|------|---------|-------------|
| `str` | `"hello"` | Text |
| `int` | `42` | Whole numbers |
| `float` | `3.14` | Decimal numbers |
| `bool` | `True` / `False` | True/false values |

---

## Basic Operators

```python
# Arithmetic
print(5 + 3)   # 8
print(5 - 3)   # 2
print(5 * 3)   # 15
print(5 / 3)   # 1.666...
print(5 // 3)  # 1  (floor division)
print(5 % 3)   # 2  (remainder)
print(5 ** 2)  # 25 (exponent)

# Comparison
print(5 == 3)  # False
print(5 != 3)  # True
print(5 > 3)   # True
```

---

## Strings

Strings are sequences of text, wrapped in quotes.

```python
greeting = "Hello"
name = "World"

# Concatenation
message = greeting + ", " + name + "!"
print(message)  # Hello, World!

# f-strings (recommended way to format strings)
print(f"{greeting}, {name}!")

# Useful string methods
print("hello".upper())      # HELLO
print("HELLO".lower())      # hello
print("  hi  ".strip())     # "hi"
print(len("hello"))         # 5
```

---

## Lists

Lists hold multiple values in a single variable.

```python
fruits = ["apple", "banana", "cherry"]

print(fruits[0])       # apple (indexing starts at 0)
print(fruits[-1])      # cherry (last item)

fruits.append("date")  # add an item
fruits.remove("banana") # remove an item

print(len(fruits))     # number of items
print(fruits)
```

---

## Conditionals

Use `if`, `elif`, and `else` to make decisions in your code.

```python
age = 18

if age < 13:
    print("Child")
elif age < 18:
    print("Teenager")
else:
    print("Adult")
```

---

## Loops

**For loops** iterate over a sequence:

```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)

for i in range(5):   # 0, 1, 2, 3, 4
    print(i)
```

**While loops** repeat as long as a condition is true:

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

---

## Functions

Functions let you package reusable blocks of code.

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))  # Hello, Alice!

def add(a, b=0):        # b has a default value
    return a + b

print(add(3, 4))   # 7
print(add(3))       # 3
```

---

## Next Steps

Now that you know the basics, try:

- **Practice**: Solve small problems on sites like [HackerRank](https://www.hackerrank.com/) or [Exercism](https://exercism.org/)
- **Explore data structures**: dictionaries, tuples, and sets
- **Learn modules**: `import` statements and Python's standard library
- **Build something**: a to-do list app, a simple calculator, or a text-based game

Happy coding! 🐍
