# Class 5 Reading Notes

## Big O Notation

Big O is used to describe the efficiency of an algorithim based on 2 factors: Time and Space
In order to analyze these limiting factors, we should consider 4 Key Areas for analysis:

- Input Size
- Units of Measurement
- Orders of Growth
- Best Case, Worst Case, and Average Case

### Input Size

Input Size refers to the size of the parameter values that are read by the algorithm.
The higher this input, the more likely there will be an increase to Running Time and Memory Space.

### Units of measurement

Three Measurements of time to quantify the Running Time:

1. The time in milliseconds from the start of a function execution until it ends.
2. The number of operations that are executed.
3. The number of “Basic Operations” that are executed.

Four sources of memory usage to quantify Memory Space:

1. The amount of space needed to hold the code for the algorithm.
2. The amount of space needed to hold the input data.
3. The amount of space needed for the output data.
4. The amount of space needed to hold working space during the calculation.

## Linked Lists

A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.
When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing.
The best way to approach a traversal is through the use of a while() loop.

---

### Resources

[Big O Analysis](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)

[Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

[What Are Linked Lists](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)

---

[Back to Home](../README.md)
