---
title: "Python CheatSheet (2025)"
source: "https://www.geeksforgeeks.org/python/python-cheat-sheet/"
author:
  - "[[GeeksforGeeks]]"
published: 2023-06-09
created: 2026-01-13
description: "Your All-in-One Learning Portal: GeeksforGeeks is a comprehensive educational platform that empowers learners across domains-spanning computer science and programming, school education, upskilling, commerce, software tools, competitive exams, and more."
tags:
  - "clippings"
---

# Python CheatSheet (2025)

Last Updated: 23 Jul, 2025

****Python****EHOLDER}**EHOLDER}**EHOLDER}**Python** is one of the most widely-used and popular programming languages, was developed by Guido van Rossum and released first in 1991. Python is a free and open-source language with a very simple and clean syntax which makes it easy for developers to **EHOLDER}**Python**. It supports object-oriented programming and is most commonly used to perform general-purpose programming.

## Why Python?

- **R}**R}**Python**–Clean, readable syntax that feels like plain English.
- **}**R}**o cost, no restrictions—just pure coding freedom.
- **Python**R}**}**ultiple programming paradigms.
- ****learn Python****libraries, frameworks and active contributors.

## Where is Python Used?

- [****Data Science****](https://www.geeksforgeeks.org/data-science/data-science/) **learn Python**}**learn Python** [****Machine Learning****](https://www.geeksforgeeks.org/machine-learning/machine-learning/)–AI, analytics and automation.
- [****Web Development****](https://www.geeksforgeeks.org/python/python-web-development/)–Frameworks like Django & Flask for building web apps.
- [****Automation****](https://www.geeksforgeeks.org/python/python-automation/) **learn Python**_PLACEHOLDER}**–Simplifying repetitive tasks.
- [****Game Development****](https://www.geeksforgeeks.org/blogs/python-game-development/)–Used in game engines and AI-driven gaming.
- [****Cybersecurity****](https://www.geeksforgeeks.org/python/python-for-cybersecurity/) **LACEHOLDER}**}**R}** [****Networking****](https://www.geeksforgeeks.org/python/python-network-programming/)–Writing security tools and network automation.

Table of Content

- [Python Basics](https://www.geeksforgeeks.org/python/python-cheat-sheet/#first-python-program)
- [Operators in Python](https://www.geeksforgeeks.org/python/python-cheat-sheet/#operators-in-python)
- [Control Flow](https://www.geeksforgeeks.org/python/python-cheat-sheet/#control-flow)
- [Python Functions](https://www.geeksforgeeks.org/python/python-cheat-sheet/#functions)
- [Data Structures in Python](https://www.geeksforgeeks.org/python/python-cheat-sheet/#data-structures-in-python)
- [Python Built-In Function](https://www.geeksforgeeks.org/python/python-cheat-sheet/#python-buildin-function)
- [Python OOPs Concepts](https://www.geeksforgeeks.org/python/python-cheat-sheet/#python-oops-concepts)
- [Python RegEx](https://www.geeksforgeeks.org/python/python-cheat-sheet/#python-regex)
- [Exception Handling in Python](https://www.geeksforgeeks.org/python/python-cheat-sheet/#exception-handling-in-python)
- [Debugging in Python](https://www.geeksforgeeks.org/python/python-cheat-sheet/#debugging-in-python)
- [File Handling in Python](https://www.geeksforgeeks.org/python/python-cheat-sheet/#file-handling-in-python)
- [Memory Management in Python](https://www.geeksforgeeks.org/python/python-cheat-sheet/#memory-management-in-python)
- [Decorators in Python](https://www.geeksforgeeks.org/python/python-cheat-sheet/#decorators-in-python)
- [Libraries in Python](https://www.geeksforgeeks.org/python/python-cheat-sheet/#libraries-in-python)
- [Python Modules](https://www.geeksforgeeks.org/python/python-cheat-sheet/#python-modules)
- [Python Interview Questions Answers](https://www.geeksforgeeks.org/python/python-cheat-sheet/#python-interview-questions-answers)

> To master python from scratch, you can refer to our article: [Python Tutorial](https://www.geeksforgeeks.org/python/python-programming-language-tutorial/)

# Python Basics

## Printing Output

[print() function](https://www.geeksforgeeks.org/python/python-print-function/) in Python is used to print Python objects as strings as standard output. [keyword end](https://www.geeksforgeeks.org/python/gfact-50-python-end-parameter-in-print/) can be used to avoid the new line after the output or end the output with a different string.

```
# python program to print "Hello World"
```

```
print("Hello World")
```

```
​
```

```
# ends the output with a space
```

```
print("Welcome to", end=' ')
```

```
print("GeeksforGeeks", end=' ')
```

**learn Python**etween the inputs to the print() method in Python is by default a space, however, this can be changed to any character, integer, or string of our choice. The ['sep' argument](https://www.geeksforgeeks.org/python/python-sep-parameter-print/) is used to do the same thing.

```
# code for disabling the softspace feature
```

```
print('09', '12', '2016', sep='-')
```

```
​
```

```
# another example
```

```
print('Example', 'geeksforgeeks', sep='@')
```

## Python Input

[input()](https://www.geeksforgeeks.org/python/python-input-function/) method in Python is used to accept user input. By default, it returns the user input as a string. By default, the input() function accepts user input as a string.

```
# Python program showing
```

```
# a use of input()
```

```
val = input("Enter your value: ")
```

```
print(val)
```

****Easy to Learn****

```
Enter your value: Hello Geeks
Hello Geeks
```

## Python Comment

[Comments in Python](https://www.geeksforgeeks.org/python/python-comments/) are the lines in the code that are ignored by the interpreter during the execution of the program. There are three types of comments in Python:

- Single line Comments
- Multiline Comments
- Docstring Comments

**Easy to Learn**

```
geeksforgeeks
```

## Variables and Data Types

Variables store values and Python supports multiple data types.

```
# Variable Declaration
```

```
x = "Hello World"
```

```
​
```

```
# DataType Output: int
```

```
x = 50
```

```
​
```

```
# DataType Output: float
```

```
x = 60.5
```

```
​
```

```
# DataType Output: complex
```

```
x = 3j
```

## Type Checking and Conversion

We can check the data type of a variable using [type()](https://www.geeksforgeeks.org/python/python-type-function/) and convert types if needed.

```
print(type(x))  # <class 'int'>
```

```
y = int(y)      # Convert float to int
```

# Operators in Python

In general, [Operators](https://www.geeksforgeeks.org/python/python-operators/) are used to execute operations on values and variables. These are standard symbols used in logical and mathematical processes.

- [Arithmetic Operators](https://www.geeksforgeeks.org/python/assignment-operators-in-python/) are used to perform mathematical operations.
- [Comparison Operators](https://www.geeksforgeeks.org/python/relational-operators-in-python/) compare values and return True or False based on the criteria.
- [Logical operators](https://www.geeksforgeeks.org/python/python-logical-operators/) are used on conditional statements in Python (either True or False).
- [Bitwise operators](https://www.geeksforgeeks.org/python/python-bitwise-operators/) are used in Python to do bitwise operations on integers.

# Control Flow

## Conditional Statements

Used to execute different blocks of code based on conditions.

```
x = 10
```

```
if x > 5:
```

```
print("x is greater than 5")
```

```
elif x == 5:
```

```
print("x is 5")
```

```
else:
```

```
print("x is less than 5")
```

## Loops

[Loops](https://www.geeksforgeeks.org/python/loops-in-python/) help iterate over sequences or repeat actions.

****&******Easy to Learn****CK_PLACEHOLDER}

```
for i in range(5):
```

**&**Easy to Learn**

```
print(i)  # Prints 0 to 4
```

```
i = 0
```

```
while i < 5:
```

```
print(i)
```

## Loop Control Statements

[Loop Control Statements](https://www.geeksforgeeks.org/dsa/loops-and-control-statements-continue-break-and-pass-in-python/) include break and continue.

break exits the loop, while continue skips the current iteration.

```
i += 1
```

```
for i in range(10):
```

```
if i == 5:
```

```
break  # Exits loop
```

```
if i == 3:
```

```
continue  # Skips iteration
```

****&****op? Wrap an iterable with ‘enumerate’ and it will yield the item along with its index. See this code snippet

```
print(i)
```

```
vowels=['a','e','i','o','u']
```

```
for i, letter in enumerate(vowels):
```

**Easy to Learn**

```
print (i, letter)
```

# Python Functions

[Python Functions](https://www.geeksforgeeks.org/python/python-functions/) are a collection of statements that serve a specific purpose. The idea is to bring together some often or repeatedly performed actions and construct a function so that we can reuse the code included in it rather than writing the same code for different inputs over and over.

```
0 a
1 e
2 i
3 o
4 u
```

```
# A simple Python function
```

```
def fun():
```

```
print("Welcome to GFG")
```

```
​
```

```
# Driver code to call a function
```

**Free & Open-Source**DER}**

```
fun()
```

## Function Arguments

Arguments are the values given between the function's parenthesis. A function can take as many parameters as it wants, separated by commas.

```
Welcome to GFG
```

```
# A simple Python function to check
```

```
# whether x is even or odd
```

```
def evenOdd(x):
```

```
if (x % 2 == 0):
```

```
print("even")
```

```
else:
```

```
print("odd")
```

```
​
```

```
​
```

```
# Driver code to call the function
```

```
evenOdd(2)
```

**Free & Open-Source**CK_PLACEHOLDER}

## Return Statement in Python Function

The function [return statement](https://www.geeksforgeeks.org/python/python-return-statement/) is used to terminate a function and return to the function caller with the provided value or data item.

```
evenOdd(3)
```

```
even
odd
```

```
# Python program to
```

```
# demonstrate return statement
```

```
def add(a, b):
```

```
​
```

```
# returning sum of a and b
```

```
return a + b
```

```
​
```

```
def is_true(a):
```

```
​
```

```
# returning boolean of a
```

```
return bool(a)
```

```
​
```

```
# calling function
```

```
res = add(2, 3)
```

```
print("Result of add function is {}".format(res))
```

```
​
```

**Free & Open-Source**LACEHOLDER}

## The range() Function

The [Python range()](https://www.geeksforgeeks.org/python/python-range-function/) function returns a sequence of numbers, in a given range.

```
res = is_true(2<5)
```

```
print("\nResult of is_true function is {}".format(res))
```

```
Result of add function is 5

Result of is_true function is True
```

```
# print first 5 integers
```

```
# using python range() function
```

**Free & Open-Source**

```
for i in range(5):
```

## \*args And \*\*kwargs in Python

The [\*args and \*\*kwargs](https://www.geeksforgeeks.org/python/args-kwargs-python/) keywords allow functions to take variable-length parameters. The number of non-keyworded arguments and the action that can be performed on the tuple are specified by the \*args.\*\*kwargs, on the other hand, pass a variable number of keyword arguments dictionary to function, which can then do dictionary operations.

```
print(i, end=" ")
```

```
print()
```

```
0 1 2 3 4
```

```
def myFun(arg1, arg2, arg3):
```

```
print("arg1:", arg1)
```

```
print("arg2:", arg2)
```

```
print("arg3:", arg3)
```

```
​
```

```
​
```

```
# Now we can use *args or **kwargs to
```

```
# pass arguments to this function :
```

```
args = ("Geeks", "for", "Geeks")
```

```
myFun(*args)
```

**ER}****Object-Oriented & Versatile****

```
​
```

**Output:**values from a function. Python allows us to return multiple values by separating them with commas. These values are implicitly packed into a tuple and when the function is called, the tuple is returned

```
kwargs = {"arg1": "Geeks", "arg2": "for", "arg3": "Geeks"}
```

```
myFun(**kwargs)
```

```
arg1: Geeks
arg2: for
arg3: Geeks
arg1: Geeks
arg2: for
arg3: Geeks
```

```
def func():
```

```
return 1, 2, 3, 4, 5
```

**Object-Oriented & Versatile**LOCK_PLACEHOLDER}

# Data Structures in Python

## List in Python

[Python list](https://www.geeksforgeeks.org/python/python-lists/) is a sequence data type that is used to store the collection of data. Tuples and String are other types of sequence data types.

```
​
```

```
one, two, three, four, five = func()
```

****&****Object-Oriented & Versatile**

```
print(one, two, three, four, five)
```

**For Loop:**A Python [list comprehension](https://www.geeksforgeeks.org/python/python-list-comprehension/) is made up of brackets carrying the expression, which is run for each element, as well as the for loop, which is used to iterate over the Python list's elements.

> Also, Read - [Python Array](https://www.geeksforgeeks.org/python/python-arrays/)

```
1 2 3 4 5
```

```
Var = ["Geeks", "for", "Geeks"]
```

```
print(Var)
```

```
['Geeks', 'for', 'Geeks']
```

```
# Using list comprehension to iterate through loop
```

**&**Object-Oriented & Versatile**

```
List = [character for character in [1, 2, 3]]
```

**Object-Oriented & Versatile**} Python in the late 1980s, lists were an essential part of the language from the very first version (Python 1.0, released in 1991). Unlike languages like [C](https://www.geeksforgeeks.org/c/c-language-introduction/) or [Java](https://www.geeksforgeeks.org/java/java-programming-basics/), where arrays have strict rules.
- ****Interesting Facts about Loops in Python:****as influenced by the ABC programming language, which also had a simple and intuitive way of handling sequences. However, Python improved upon it by making lists mutable (meaning they can be changed), which is one of the biggest reasons for their popularity.

> Explore in detail about [Interesting Facts About Python Lists](https://www.geeksforgeeks.org/python/interesting-facts-about-python-lists/)

## Dictionary in Python

A [dictionary in Python](https://www.geeksforgeeks.org/python/python-dictionary/) is a collection of key values, used to store data values like a map, which, unlike other data types holds only a single value as an element.

```
​
```

```
# Displaying list
```

**LDER}**LACEHOLDER}

****1\. Using enumerate to Get Index and Value in a Loop:****ist Comprehension, Python allows [dictionary comprehension](https://www.geeksforgeeks.org/python/python-dictionary-comprehension/). We can create dictionaries using simple expressions. A dictionary comprehension takes the form {key: value for (key, value) in iterable}

```
print(List)
```

```
[1, 2, 3]
```

```
Dict = {1: 'Geeks', 2: 'For', 3: 'Geeks'}
```

```
print(Dict)
```

```
{1: 'Geeks', 2: 'For', 3: 'Geeks'}
```

```
# Lists to represent keys and values
```

```
keys = ['a','b','c','d','e']
```

```
values = [1,2,3,4,5]
```

```
​
```

```
# but this line shows dict comprehension here
```

```
myDict = { k:v for (k,v) in zip(keys, values)}
```

****Massive Community Support****

```
​
```

**Python sep parameter in print()**thon 3.7, [dictionaries](https://www.geeksforgeeks.org/python/python-dictionary/) did not preserve the order of insertion. However, with the introduction of Python 3.7 and beyond, dictionaries now maintain the order of the key-value pairs. Now we can rely on the insertion order of keys when iterating through dictionaries, which was previously a feature exclusive to [****OrderedDict****](https://www.geeksforgeeks.org/python/ordereddict-in-python/).
- **&**Massive Community Support** immutable, meaning they can be [strings](https://www.geeksforgeeks.org/python/python-string/), numbers or [tuples](https://www.geeksforgeeks.org/python/tuples-in-python/), but not [lists](https://www.geeksforgeeks.org/python/python-lists/) or other mutable types. This feature ensures that the dictionary keys are hashable, maintaining the integrity and performance of lookups.

> Explore in detail about [Interesting Facts About Python Dictionary](https://www.geeksforgeeks.org/python/interesting-facts-about-python-dictionary/)

## Tuples in Python

[Tuple](https://www.geeksforgeeks.org/python/python-tuples/) is a list-like collection of Python objects. A tuple stores a succession of values of any kind, which are indexed by integers.

```
# We can use below too
```

```
# myDict = dict(zip(keys, values))
```

**Massive Community Support**

```
​
```

## Sets in Python

[Python Set](https://www.geeksforgeeks.org/python/python-sets/) is an unordered collection of data types that can be iterated, mutated and contains no duplicate elements. The order of the elements in a set is unknown, yet it may contain several elements.

```
print (myDict)
```

```
{'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}
```

**Massive Community Support**

```
var = ("Geeks", "for", "Geeks")
```

## Python String

In Python, a string is a data structure that represents a collection of characters. A string cannot be changed once it has been formed because it is an immutable data type.

****For Loop:****Python can be created using single quotes or double quotes or even triple quotes. In Python, individual characters of a String can be accessed by using the method of Indexing. Indexing allows negative address references to access characters from the back of the String.

```
print(var)
```

```
('Geeks', 'for', 'Geeks')
```

```
var = {"Geeks", "for", "Geeks"}
```

```
print(var)
```

```
{'for', 'Geeks'}
```

```
String1 = "GeeksForGeeks"
```

```
print("Initial String: ")
```

```
print(String1)
```

```
​
```

```
# Printing First character
```

```
print("\nFirst character of String is: ")
```

**Massive Community Support**

```
print(String1[0])
```

****While Loop:****R} in Python can be constructed with single, double, or even triple quotes. The slicing method is used to access a single character or a range of characters in a String. A Slicing operator (colon) is used to slice a String.

```
​
```

```
# Printing Last character
```

```
print("\nLast character of String is: ")
```

```
print(String1[-1])
```

```
Initial String: 
GeeksForGeeks

First character of String is: 
G

Last character of String is: 
s
```

```
# Creating a String
```

```
String1 = "GeeksForGeeks"
```

```
print("Initial String: ")
```

```
print(String1)
```

```
​
```

```
# Printing 3rd character
```

```
print("\nSlicing characters from 3-12: ")
```

```
print(String1[3])
```

```
​
```

**HOLDER}**LACEHOLDER}

****1\. One can return multiple values in Python:****ble, once a string is defined, it cannot be changed.
- Strings Can Be Concatenated Using the + Operator: We can easily combine (concatenate) strings using the + operator. This simple operation allows us to build longer strings from smaller ones, which is helpful when working with user input or constructing strings dynamically.

> Explore in detail about [Strings](https://www.geeksforgeeks.org/python/python-string/)

> Explore in Detail [Interesting Facts about Python Strings](https://www.geeksforgeeks.org/python/interesting-facts-about-strings-in-python-set-1/)

# Python Built-In Function

There are numerous [Python Data Structures and Algorithms](https://www.geeksforgeeks.org/dsa/python-data-structures-and-algorithms/) that make creating code easier. Learn about the built-in functions of Python in this post as we examine their numerous uses and highlight a few of the most popular ones.

> For More Read, refer [built-in methods in Python](https://www.geeksforgeeks.org/python/python-built-in-functions/)

# Python OOPs Concepts

[Python Built in Functions](https://www.geeksforgeeks.org/python/python-built-in-functions/) (OOPs) is a programming paradigm in Python that employs objects and classes. It seeks to include real-world entities such as inheritance, polymorphisms, encapsulation and so on into programming. The primary idea behind OOPs is to join the data and the functions that act on it as a single unit so that no other portion of the code can access it.

- [Object-oriented Programming](https://www.geeksforgeeks.org/python/python-oops-concepts/)
- [Class And Objects](https://www.geeksforgeeks.org/python/python-classes-and-objects/)
- [Polymorphism](https://www.geeksforgeeks.org/python/polymorphism-in-python/)
- [Encapsulation](https://www.geeksforgeeks.org/python/encapsulation-in-python/)
- [Inheritance](https://www.geeksforgeeks.org/python/inheritance-in-python/)

In this example, we have a Car class with characteristics that represent the car's make, model and year. The \_make attribute is protected with a single underscore \_. The \_\_model attribute is marked as private with two underscores \_\_. The year attribute is open to the public.

We can use the getter function get\_make() to retrieve the protected attribute \_make. We can use the setter method set\_model() to edit the private attribute \_\_model. Using the getter method get\_model(), we may retrieve the changed private attribute \_\_model. There are no restrictions on accessing the public attribute year. We manage the visibility and accessibility of class members by using encapsulation with private and protected properties, offering a level of data hiding and abstraction.

```
# Printing characters between
```

```
# 3rd and 2nd last character
```

```
print("\nSlicing characters between " +
```

```
"3rd and 2nd last character: ")
```

```
print(String1[3:-2])
```

```
Initial String: 
GeeksForGeeks

Slicing characters from 3-12: 
k

Slicing characters between 3rd and 2nd last character: 
ksForGee
```

```
class Car:
```

```
def __init__(self, make, model, year):
```

```
self._make = make  # protected attribute
```

```
self.__model = model  # private attribute
```

```
self.year = year  # public attribute
```

```
​
```

```
def get_make(self):
```

```
return self._make
```

```
​
```

```
def set_model(self, model):
```

```
self.__model = model
```

```
​
```

```
def get_model(self):
```

```
return self.__model
```

```
​
```

```
​
```

**HOLDER}**

```
my_car = Car("Toyota", "Corolla", 2022)
```

**Interesting Facts about Loops in Python:**s flexibility. Python supports several programming paradigms, including:

- Object-Oriented Programming (OOP)
- Functional Programming
- Procedural Programming

**LDER}** is an object, including data types such as integers, strings and functions. This allows for object-oriented programming (OOP) principles to be applied across all aspects of the language, including the ability to define classes, inheritance and methods.

```
​
```

```
print(my_car.get_make())  # Accessing protected attribute
```

```
my_car.set_model("Camry")  # Modifying private attribute
```

```
print(my_car.get_model())  # Accessing modified private attribute
```

```
print(my_car.year)  # Accessing public attribute
```

```
Toyota
Camry
2022
```

```
x = 5
```

```
​
```

```
# <class 'int'>
```

**ER}**HOLDER}**```
print(type(greet))

```
print(type(x))
```

<class 'int'>

<class 'function'>

```
​
```

import re

```
def greet(name):
```

```
return f"Hello, {name}"
```

# Text to search

```
# <class 'function'>
```

text = "Hello, my email is example@example.com"

```

# Python RegEx

We define a pattern using a [Data Abstraction](https://www.geeksforgeeks.org/python/abstract-classes-in-python/) to match email addresses. The pattern r"\\b\[A-Za-z0-9.\_%+-\]+@\[A-Za-z0-9.-\]+\\.\[A-Za-z\]{2,}\\b" is a common pattern for matching email addresses. Using the re.search() function, the pattern is then found in the given text. If a match is found, we use the match object's group() method to extract and print the matched email. Otherwise, a message indicating that no email was found is displayed.

```

```

```

# Define a Pattern to Match Email Addresses

```

```

pattern = r"\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}\b"

```

```

```

```

# Search for the Pattern in the Text

```

```

match = re.search(pattern, text)

```

```

```

```

# Check if a Match is Found

```

```

if match:

```

```

email = match.group()

```

```

print("Found email:", email)

```

```

else:

```

```

print("No email found.")

```

```

Found email: example@example.com

```

```

a = [1, 2, 3]

```

```

try:

```

```

print ("Second element = %d" %(a[1]))

```

**Output**

```

```

MetaCharacters are helpful, significant and will be used in module re functions, which helps us comprehend the analogy with RE. The list of metacharacters is shown below.

- **Output**PLACEHOLDER}** sed to drop the special meaning of character following it.
- \[\] Represent a character class.
- ^ Matches the beginning.
- $ Matches the end.
- . Matches any character except newline.
- | Means OR (Matches with any of the characters separated by it.
- ? Matches zero or one occurrence.
- \* Any number of occurrences (including 0 occurrences).
- \+ One or more occurrences.
- {} Indicate the number of occurrences of a preceding RegEx to match.
- () Enclose a group of RegEx.

> For More RegEx example, refer to [regular expression](https://www.geeksforgeeks.org/python/python-regex/).

# Exception Handling in Python

In Python, [Python RegEx](https://www.geeksforgeeks.org/python/python-regex/) are used to catch and manage exceptions. Statements that can raise exceptions are kept inside the try clause and the statements that handle the exception are written inside except clause.

```

# Throws Error since there Are only 3 Elements in Array

```

```

print ("Fourth element = %d" %(a[3]))

```

```

```

```

except:

```

```

print ("An error occurred")

```

```

Second element = 2

An error occurred

```

```

x = 10

```

```

y = 20

```

```

print("x:", x)

```

**Output**ER}

# Debugging in Python

Debugging is the process of finding and fixing errors (bugs) in our code. Python provides several methods and tools to help debug programs effectively.

## 1\. Using Print Statements

```

print("y:", y)

```

```

result = x + y

```

```

print("result:", result)

```

```

x: 10

y: 20

result: 30

```

```

> /home/repl/2b752c75-c2c1-44d7-b2bd-fa43a3072b3c/main.py(6)<module>()
-> result = x + y
(Pdb)

```

```

import logging

```

**Output**

```

```

## 2\. Using Pdb (Python Debugger)

The [Try and except statements](https://www.geeksforgeeks.org/python/python-try-except/) module provides an interactive debugging environment. We can set breakpoints, step through the code, inspect variables and more. To start debugging, insert pdb.set\_trace() where we want to start the debugger.

`  ``` import pdb  x = 5 y = 10 pdb.set_trace()  # Debugger starts here result = x + y print(result) ```  `

****Lists Have Been in Python Since the Beginning:****Output**

```

# Set up Logging Configuration

```

Once the program reaches pdb.set\_trace(), it will enter the interactive mode where we can run various commands like:

- **Lists Have Been in Python Since the Beginning:****Interesting Facts about Functions in Python:**** Execute the next line of code.
- ****Inspired by ABC Language:****Interesting Facts about Functions in Python:** Step into a function.
- **Interesting Facts about Functions in Python:**}** Continue execution until the next breakpoint.
- **1\. One can return multiple values in Python:**LDER}** Exit the debugger.

## 3\. Using Logging Module

The logging module is more advanced than print() statements and is useful for debugging in production environments. It allows us to log messages with different severity levels (DEBUG, INFO, WARNING, ERROR, CRITICAL).

```

logging.basicConfig(level=logging.DEBUG)

```

```

```

```

# Log Different Messages

```

```

logging.debug("This is a debug message")

```

```

logging.info("This is an info message")

```

```

logging.warning("This is a warning message")

```

```

logging.error("This is an error message")

```

```

logging.critical("This is a critical message")

```

```

DEBUG:root:This is a debug message

INFO:root:This is an info message

WARNING:root:This is a warning message

ERROR:root:This is an error message

CRITICAL:root:This is a critical message

```

```

import os

```

```

```

**Output****

```

def create_file(filename):

```

# File Handling in Python

Python too supports [pdb](https://www.geeksforgeeks.org/python/python-debugger-python-pdb/) and allows users to handle files i.e., to read and write files, along with many other file handling options, to operate on files.

```

try:

```

```

with open(filename, 'w') as f:

```

```

f.write('Hello, world!\n')

```

```

print("File " + filename + " created successfully.")

```

```

except IOError:

```

```

print("Error: could not create file " + filename)

```

```

```

```

def read_file(filename):

```

```

try:

```

```

with open(filename, 'r') as f:

```

```

contents = f.read()

```

```

print(contents)

```

```

except IOError:

```

```

print("Error: could not read file " + filename)

```

```

```

```

def append_file(filename, text):

```

```

try:

```

```

with open(filename, 'a') as f:

```

```

f.write(text)

```

```

print("Text appended to file " + filename + " successfully.")

```

```

except IOError:

```

```

print("Error: could not append to file " + filename)

```

```

```

```

def rename_file(filename, new_filename):

```

```

try:

```

```

os.rename(filename, new_filename)

```

```

print("File " + filename + " renamed to " +

```

```

new_filename + " successfully.")

```

```

except IOError:

```

```

print("Error: could not rename file " + filename)

```

```

```

```

def delete_file(filename):

```

```

try:

```

```

os.remove(filename)

```

```

print("File " + filename + " deleted successfully.")

```

```

except IOError:

```

```

print("Error: could not delete file " + filename)

```

```

```

```

```

```

if **&** == '****Python sep parameter in print()****':

```

```

filename = "example.txt"

```

```

new_filename = "new_example.txt"

```

```

```

```

create_file(filename)

```

```

read_file(filename)

```

```

append_file(filename, "This is some additional text.\n")

```

```

read_file(filename)

```

```

rename_file(filename, new_filename)

```

```

read_file(new_filename)

```

```

delete_file(new_filename)

```

```

File example.txt created successfully.

Hello, world!

Text appended to file example.txt successfully.

Hello, world!

This is some additional text.

File example.txt renamed to new_example.txt successfu…

```

```

import sys

```

```

x = 10

```

**Output**

```

y = [1, 2, 3]

```

## Reading and Writing Files

Python provides built-in functions to handle file operations such as reading from and writing to files. We can use the open() function to work with files.

****List comprehension****
The open() function is used to open a file and returns a file object.

`  ``` file = open('filename.txt', 'mode') ```  `

- **List comprehension**t mode) - Opens the file for reading.
- **List comprehension**ACEHOLDER}** Write - Opens the file for writing (creates a new file or overwrites an existing one).
- ****Dictionaries Are Ordered:****Output** Append - Opens the file for appending data.
- **Dictionaries Are Ordered:****Interesting Facts about Lists in Python**** Read/Write in binary mode.

****Dictionaries Can Have Any Immutable Type as Keys:****e are several methods to read the contents of a file:

- read()
- readline()
- readlines()
`  ``` with open('example.txt', 'r') as file:     # Using read()     content = file.read()      print(content)          # Resetting the pointer to the beginning of the file     file.seek(0)          # Using readline()     first_line = file.readline()      print(first_line)          # Resetting the pointer again     file.seek(0)          # Using readlines()     lines = file.readlines()       print(lines) ```  `

**Interesting Facts about Lists in Python** can write data to a file using the `write()` or `writelines()` methods:

**Interesting Facts about Lists in Python**OLDER}** Writes a string to the file.

`  ``` with open('filename.txt', 'w') as file:     file.write("Hello, World!") ```  `

**EHOLDER}**}** Writes a list of strings to the file.

`  ``` with open('filename.txt', 'w') as file:     file.writelines(['Hello\n', 'World\n']) ```  `

**LDER}**ctice to close the file after operations using file.close(), but it is recommended to use the with statement as it automatically handles file closure.

`  ``` file.close() ```  `

# Memory Management in Python

[file handling](https://www.geeksforgeeks.org/python/file-handling-python/) is handled by the Python memory manager. Python uses an automatic memory management system, which includes garbage collection to reclaim unused memory and reference counting to track memory usage.

## Key Concepts

1. **LDER}**Every object in Python has a reference count. When the count reaches zero, the object is deleted automatically.
2. **Inspired by ABC Language:**Python uses a garbage collector to clean up circular references (when objects reference each other in a cycle).

```

```

```

# Checking Memory Size of Variables

```

```

print("Memory size of x:", sys.getsizeof(x))

```

```

print("Memory size of y:", sys.getsizeof(y))

```

```

```

```

# Reference counting

```

```

a = [1, 2, 3]

```

```

b = a

```

```

print(sys.getrefcount(a))

```

```

Memory size of x: 28

Memory size of y: 88

3

```

```

@property

```

```

def name(self):

```

**Output****

```

return self.__name

```

# Decorators in Python

Decorators are used to modifying the behavior of a function or a class. They are usually called before the definition of a function we want to decorate.

# 1\. Property Decorator (getter)

```

@name.setter

```

```

def name(self, value):

```

```

self.__name=value

```

# 2\. Setter Decorator

It is used to set the property 'name'

```

@name.deleter

```

```

def name(self, value):

```

```

print('Deleting..')

```

# 3\. Deleter Decorator

It is used to delete the property 'name'

```

del self.__name

```

```
