Loops in Python

What Are Loops?

Loops repeat a block of code. Python has two main loop types: for and while.

The for Loop

A for loop iterates over the elements of an iterable, such as a list, string, or range.

for name in ["Alex", "John", "Sam"]:
    print(name)

The range() Function

range() generates a sequence of integers.

range(5)        # 0, 1, 2, 3, 4
range(2, 6)     # 2, 3, 4, 5
range(0, 10, 2) # 0, 2, 4, 6, 8

The stop value is excluded.

for i in range(3):
    print(i)

Output: 0 1 2

The while Loop

A while loop repeats as long as its condition remains true.

count = 0
while count < 3:
    print(count)
    count += 1

Make sure the condition eventually becomes false to avoid an infinite loop.

break and continue

* break immediately terminates the nearest enclosing loop.
* continue skips the rest of the current iteration and proceeds to the next one.

for i in range(5):
    if i == 2:
        continue
    if i == 4:
        break
    print(i)

Output: 0 1 3

The else Clause

Loops can have an else clause. It executes when the loop finishes normally, without being terminated by break.

for i in range(3):
    print(i)
else:
    print("Loop completed")

Nested Loops

A nested loop is a loop inside another loop.

for i in range(2):
    for j in range(3):
        print(i, j)

For every iteration of the outer loop, the inner loop runs completely.

Iterating Over Collections

numbers = [10, 20, 30]
for number in numbers:
    print(number)
for index, number in enumerate(numbers):
    print(index, number)
user = {"name": "Alex", "age": 18}
for key, value in user.items():
    print(key, value)

enumerate() provides an index and an element. The dictionary method items() provides key-value pairs.

Important

* Use for when iterating over a sequence or iterable.
* Use while when repetition depends on a condition.
* Use break to exit a loop.
* Use continue to skip an iteration.
* Be careful when modifying a collection while iterating over it.