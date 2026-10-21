# Operators in Python

Operators perform operations on values and variables.

# Arithmetic Operators

* + — addition: 5 + 2 returns 7.
* - — subtraction: 5 - 2 returns 3.
* * — multiplication: 5 * 2 returns 10.
* / — division: 5 / 2 returns 2.5.
* // — floor division: 5 // 2 returns 2.
* % — modulo (remainder): 5 % 2 returns 1.
* ** — exponentiation: 2 ** 3 returns 8.

# Comparison Operators

Comparison operators return True or False.

* == — equal to.
* != — not equal to.
* > — greater than.
* < — less than.
* >= — greater than or equal to.
* <= — less than or equal to.

# Logical Operators

* and — returns True if both conditions are true.
* or — returns True if at least one condition is true.
* not — reverses a Boolean value.

age = 20
print(age >= 18 and age < 65)  # True

# Assignment Operators

Assignment operators assign or update variable values.

x = 10
x += 5   # x = x + 5
x -= 2   # x = x - 2
x *= 3   # x = x * 3
x /= 2   # x = x / 2

Other examples include //=, %=, and **=.

# Membership Operators

* in — checks whether an element exists in a collection.
* not in — checks whether an element does not exist in a collection.

print("a" in "cat")        # True
print(5 not in [1, 2, 3])  # True

# Identity Operators

* is — checks whether two references point to the same object.
* is not — checks whether two references point to different objects.

Use == to compare values and is to check object identity.

x = None
print(x is None)  # True