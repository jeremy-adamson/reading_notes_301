# Linked Lists

## Linked Lists

* Linked lists are data structures where each object has the data contained along with a reference to other nodes. A singly linked list only has one reference in the 'next' field while a doubly linked node has information about both adjacent nodes to the current one.
* For the list in general the only value that is stored in a vanilla linked list is the head or the starting point
* The only way to move through a list is to start at the head and traverse it by hopping from one node to the next through reading the value in the 'next' field.
* While traversal is O(n) operation, any value may be added with O(1) (assuming that you already know where you want the node to be added).
  * If the list is adding at the end, it will take O(n) operations but only O(1) if it's added at the front.
  * Meanwhile for a traditional list, adding at the end is O(1) but adding to the front is O(n) which is the exact opposite
* A linked list is a linear data structure at it's core BUT many non-linear structures use the main ideas of a linked list (node, data, adjacent node fields)
* While linked lists are very similar to lists (arrays), there are some differences as stated above. In addition to those the memory allocation is completely different considering for a traditional array all of the memory addresses of the cells are adjacent while for a linked list they can be in random places allowing for greater flexibility

## Readings

* [Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)
* [Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
* [What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
* [What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)
