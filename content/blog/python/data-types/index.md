---
title: Python Data Types
summary: Learning Python Data Types
date: 2026-01-11
authors:
  - admin
tags:
  - Learn
  - Python
image:
  caption: 'Image credit: [**Data Types**](https://www.miyukidemy.com/)'
---

Data types are like different kinds of boxes which define the type of things each box can hold. Data types help us organize different kinds of information when we write computer programs. For example, we use different boxes to store clothes, toys or books.

## Python Data Types

**1. The Number Box (Integers and Floats)**
* Integers (int)
  integer represents whole numbers without decimals, like counting candy, should be used integer.
* Floats (float)
  float represents numbers with decimal points, like measure height 120.5 or phi = 3.14

**2. The Word Box (Strings)**
  string represents a sequence of characters or alphabets, perfect for holding any combination of letters, numbers, or symbols.

**3. The True/False Box (Booleans)**
  boolean represents two possible values: True or False. It's like asking a yes-or-no question. 

## Let's Code

```python
name = "Miyu"   # String
age = 9       # Integer
pi = 3.14159     # Float
is_raining = True # Boolean

print(name, "is of type:", type(name))
print(age, "is of type:", type(age))
print(pi, "is of type:", type(pi))
print(is_raining, "is of type:", type(is_raining))
```
**Output**
```python
Miyu is of type: <class 'str'>
9 is of type: <class 'int'>
3.14159 is of type: <class 'float'>
True is of type: <class 'bool'>
```

## Why data type is important?
Python needs to know what kind of data to avoid confused while working. For example, if you try to add your name and your age, Python might get confused because they are different types of data.

## Test
Can you guess the outputs of the following program and explain why:

```python
print(4 + 5)
print("4" + "5")
```


{{% accordion title="Answer" %}}
9
45
{{% /accordion %}}




