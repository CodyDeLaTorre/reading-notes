# Class 30 Reading Notes

## Hash Tables

### WHY

- We use Hash Tables to hold unique values
- It's important to know the data structure of hash tables and how to create them for whiteboards and job interviews

### WHAT

- Hashtables are data structures that utilize key value pairs, objects(JS) and dictionaries(Python) are hash tables
- the basic idead is that a hashtable has the ability to hash
- hashing is the ability to encode a key that will eventually map to a specific location in the table

### HOW

A hashtable traditionally is created from an array. I always like the size 1024. this is important for index placement. After you have created your array of the appropriate size, do some sort of logic to turn that “key” into a numeric number value. Here is a simplistic hashing algorithm:

- Add or multiply all the ASCII values together.
- Multiply it by a prime number such as 599.
- Use modulo to get the remainder of the result, when divided by the total size of the array.
- Insert into the array at that index.

### What Id like to Know More About

How do you remeber how to code a hashtable off the top of your head?

---

### Resources

[Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)

[Basics of Hash Tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)

---

[Back to Home](../README.md)
