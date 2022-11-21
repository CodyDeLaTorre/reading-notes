# Class 9 Reading Notes

## Functional Programming

1. What is functional programming? Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
2. What is a pure function and how do we know if something is a pure function? A function being pure means it returns the same value if given the same arguments
3. What are the benefits of a pure function? It is easier to test code with pure functions
4. What is immutability? When data is immutable it means it can't be changed once created
5. What is Referential transparency? pure functions + immutable data = referential transparency

## Modules & Require

1. What is a module? A module is a small bit of code that has a particular functinality in the application
2. What does the word ‘require’ do? Require pulls modules into other JS files
3. How do we bring another module into the file the we are working in? We use require to grab the file that holds the module we want. Then we export the module we want form it original file
4. What do we have to do to make a module available? after exporting and requiring the module we make it a variable and use it that way

---

### Resources

[Functional Programming](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

[React: Modules and Require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

---

[Back to Home](../README.md)
