# Class 7 Reading Notes

## Python Scope

In programming, the scope of a name defines the area of a program in which you can unambiguously access that name.

- Global Scope: The names that you define in this scope are available to all your code.
- Local Scope: The names that you define in this scope are only available or visible to the code within the scope.

Python resolves names using the so-called LEGB rule, which is named after the Python scope for names. The letters in LEGB stand for Local, Enclosing, Global, and Built-in. Here’s a quick overview of what these terms mean:

- Local (or function) scope is the code block or body of any Python function or lambda expression. This Python scope contains the names that you define inside the function. These names will only be visible from the code of the function. It’s created at function call, not at function definition, so you’ll have as many different local scopes as function calls. This is true even if you call the same function multiple times, or recursively. Each call will result in a new local scope being created.
- Global (or module) scope is the top-most scope in a Python program, script, or module. This Python scope contains all of the names that you define at the top level of a program or a module. Names in this Python scope are visible from everywhere in your code.

Modifying global names is generally considered bad programming practice because it can lead to code that is:

- Difficult to debug: Almost any statement in the program can change the value of a global name.
- Hard to understand: You need to be aware of all the statements that access and modify global names.
- Impossible to reuse: The code is dependent on global names that are specific to a concrete program.

Good programming practice recommends using local names rather than global names. Here are some tips:

- Write self-contained functions that rely on local names rather than global ones.
- Try to use unique objects names, no matter what scope you’re in.
- Avoid global name modifications throughout your programs.
- Avoid cross-module name modifications.
- Use global names as constants that don’t change during your program’s execution.

---

### Resources

[Python Scope](https://realpython.com/python-scope-legb-rule/)

---

[Back to Home](../README.md)
