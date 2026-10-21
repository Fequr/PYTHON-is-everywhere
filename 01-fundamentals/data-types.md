# Data Types in Python

# Basic Data Types

* int — integer numbers, e.g. 10.
* float — floating-point numbers, e.g. 3.14.
* str — text, e.g. "Hello".
* bool — Boolean values: True and False.
* NoneType — represents the absence of a value: None.

# Collection Types

* list — an ordered, mutable collection, e.g. [1, 2, 3].
* tuple — an ordered, immutable collection, e.g. (1, 2, 3).
* set — a collection of unique elements, e.g. {1, 2, 3}.
* dict — a collection of key-value pairs, e.g. {"name": "Alex"}.

# Checking Types

Use type() to check an object’s type.

age = 18
print(type(age))  # <class 'int'>

Use isinstance() to check whether an object belongs to a particular type.

print(isinstance(10, int))  # True

# Mutable vs Immutable

Mutable objects can be modified after creation. Examples include list, dict, and set.

Immutable objects cannot be modified after creation. Examples include int, float, str, tuple, and bool.

# Dynamic Typing

Python is dynamically typed. A variable can refer to objects of different types at different times.

value = 10
value = "Hello"

The type belongs to the object, not permanently to the variable.