# Class 2 Reading Notes

## Tesing and Modules

### In Tests We Trust

Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. The tests can be considered as your alive documentation. We need to be descriptive about it and to say what is expected and what we are testing.
Other thing to care about is the structure. A convention widely used is the AAA: Arrange, Act and Assert.

- Arrange: you need to organize the data needed to execute that piece of code (input);
- Act: here you will execute the code being tested (exercise the behaviour);
- Assert: after executing the code, you will check if the result (output) is the same as you were expecting.

The cycle is made by three steps:

- 🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)
- ✅ Write the feature and make the test pass! (you can dance after that)
- 🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)

### if __name__ == "__main__"

A module is a file containing Python definitions and statements. The file name is the module name with the suffix .py appended. When we execute file as command to the python interpreter,  "python script.py"

Advantages :

- Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
- If you import this script as a module in another script, the __name__ is set to the name of the script/module.
- Python files can act as either reusable modules, or as standalone programs.
- if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.

### Into to Recursion

1. What is Recursion?
The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function.

2. Need of Recursion
Recursion is an amazing technique with the help of which we can reduce the length of our code and make it easier to read.

3. Propersties of Recursion
Performing the same operations multiple times with different inputs.
In every step, we try smaller inputs to make the problem smaller.
Base condition is needed to stop the recursion otherwise infinite loop will occur.

---

### Resources

[Tests We Trust](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)

[if name = main](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)

[Recursion Intro](https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/)

---

[Back to Home](../README.md)
