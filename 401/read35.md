# Class 35 Reading Notes

## Graphs

### WHAT

- graphs are a non-linear data structure that is a collection of vertices/nodes
- undirected graph is where each vertice is bi-directional meaning the graph doesnt move in any direction
- directed graph or digraph has each node directed at eachother

### WHY

- we use graphs in GPS and mapping, driving directions, airline traffic and many more things

### HOW

- You can traverse through graphs using breadth-first similar to Binary Trees.
- Here is what the algorithm breadth first traversal looks like:

- Enqueue the declared start node into the Queue.
- Create a loop that will run while the node still has nodes present.
- Dequeue the first node from the queue
- if the Dequeue‘d node has unvisited child nodes, add the unvisited children to visited set and insert them into the queue.

---

### Resources

[Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

---

[Back to Home](../README.md)
