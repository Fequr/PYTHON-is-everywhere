Type Conversion in Python

Type conversion changes a value from one data type to another.

Explicit Conversion

Explicit conversion is performed by the programmer using built-in functions.

int("42")        # 42
float("3.14")    # 3.14
str(100)         # "100"
bool(1)          # True
list((1, 2, 3))  # [1, 2, 3]
tuple([1, 2])    # (1, 2)
set([1, 1, 2])   # {1, 2}

Implicit Conversion

Python automatically converts some values when appropriate.

result = 5 + 2.0
print(result)       # 7.0
print(type(result)) # <class 'float'>

Converting User Input

The input() function always returns a string.

age = int(input("Enter your age: "))
price = float(input("Enter a price: "))

Common Errors

Invalid conversions can raise ValueError.

int("hello")  # ValueError

Converting a floating-point number to an integer removes the fractional part. It does not round the number.

int(3.9)   # 3
int(-3.9)  # -3

Truth Value Conversion

The bool() function converts a value to True or False.

Falsy values include False, None, numeric zero, and empty strings or collections.

Examples:

bool(0)      # False
bool("")     # False
bool([])     # False
bool("0")    # True
bool([1])    # True

Most other values are truthy.

Important: bool("False") returns True because the string is not empty.