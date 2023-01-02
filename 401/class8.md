# Class 8 Reading Notes

## List Comprehensions

To understand the list comprehension, imagine it like this: you’re going to perform an expression on each item in the list. The expression will determine what item is eventually stored in the output list.

- List comprehension methods are an elegant way to create and manage lists. 
- In Python, list comprehensions are a more compact way of creating lists. 
- More flexible than for loops, list comprehension is usually faster than other methods.

### Create a List Using Loops and List Comprehension in Python

In the following example, you’ll see two different techniques for creating a Python list. The first is a for loop. We’ll use it to construct a list of the powers of two.

Example 2: Comparing list creation methods in Python

First, create a list and loop through it. Add an expression, in this example, we’ll raise x to the power of 2.

#### create a list using a for loop

squares = []

for x in range(10):
    # raise x to the power of 2
    squares.append(x**2)

print(squares)
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
Output

The same thing can be done using a list comprehension, but with a fraction of the code. Let’s take a look at how to create a list of squares using the list comprehension method.

#### create a list using list comprehension

squares = [x**2 for x in range(10)]

print(squares)
Even in this basic example, it’s obvious that list comprehensions reduce the code necessary to complete rather complicated task when working with a list.

---

### Resources

[List Comprehension in Python](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)

---

[Back to Home](../README.md)
