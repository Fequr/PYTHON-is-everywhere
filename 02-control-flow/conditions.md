Conditions in Python

What Are Conditions?

Conditions allow a program to make decisions and execute different code depending on whether a condition is True or False.

if, elif, and else

* if executes a block if its condition is true.
* elif checks another condition if the previous conditions were false.
* else executes when none of the previous conditions were true.

age = 18
if age < 18:
    print("Minor")
elif age == 18:
    print("Just turned 18")
else:
    print("Adult")

Python uses indentation to define code blocks. The standard is four spaces.

Comparison Operators

* == — equal to.
* != — not equal to.
* > — greater than.
* < — less than.
* >= — greater than or equal to.
* <= — less than or equal to.

Logical Operators

* and — all conditions must be true.
* or — at least one condition must be true.
* not — reverses a Boolean value.

age = 20
has_ticket = True
if age >= 18 and has_ticket:
    print("Access granted")

Truthy and Falsy Values

Python evaluates values as either truthy or falsy in conditions.

Falsy values include:

* False
* None
* 0 and 0.0
* Empty strings and collections, such as "", [], {}, and set().

Most other values are truthy.

name = ""
if name:
    print("Name provided")
else:
    print("Name is empty")

Conditional Expressions

A conditional expression allows you to choose a value in one line.

age = 20
status = "Adult" if age >= 18 else "Minor"

The pass Statement

pass is a placeholder that does nothing. It is useful when a statement is syntactically required but its implementation is not ready.

if age >= 18:
    pass

Important

* Conditions are evaluated from top to bottom.
* Once a branch executes, the remaining branches are skipped.
* Use == to compare values, not =.
* Avoid unnecessarily complicated nested conditions.