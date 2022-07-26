## Big O: Analysis of Algorithm Efficiency
 
Big O(oh) notation is used to describe the efficiency of an algorithm or function. This efficiency is evaluated based on 2 factors:

- Running Time also known as time efficiency / complexity.The amount of time a function needs to complete.

- Memory Space also known as space efficiency / complexity.The amount of memory resources a function uses to store data and instructions.


## Linked Lists

A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the `next Node`in the link.

- A linked list is made up of a series of nodes, which are the elements of the list.

there is 2 types of linked list - singly and doubly.

- singly linked list means there is only one reference link.
- doubly means there is two /double linked lists within the node - a reference to the next node, as well as the previous node.
- Nearly all linked lists must have a head.`Head` is always the first node/ entry point in a Linked List.
- One `node` is made up of two parts: some `data` that it holds, and a `reference` to the `next node`.
- `Traversing` means visiting each node of the list once in order to perform some operation on that.The best way to approach a traversal is through the use of a `while()` loop.When traversing through a linked list, the `Current` variable will tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end/ `NULL`.
-The fundamental difference between arrays and linked lists is that arrays are static data structures, while linked lists are dynamic data structures. 
- linked list doesn’t need a contiguous block of memory. Because a single node has the “address” or a reference to the next node, they don’t need to live right next to one another, the way that the elements have to in an array.That's why linked lists can grow and shrink dynamically and can live scattered everywhere in the memory.

`A node only knows about what data it contains, and who its neighbor is.`


## Resources
- [Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)
- [Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
- [What’s a Linked List, Anyway? [Part 1]](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
- [What’s a Linked List, Anyway? [Part 2]](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)
