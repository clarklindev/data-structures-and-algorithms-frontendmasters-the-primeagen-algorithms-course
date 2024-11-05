# frontendmasters - the-primeagen - the-last-algorithms-course-you-will-need

- [course url](https://frontendmasters.com/courses/algorithms/)
- [exercise_files](https://github.com/ThePrimeagen/kata-machine)
- [course notes](https://theprimeagen.github.io/fem-algos/)
- total time: 9 hours, 20 minutes

## Table of Contents

---

### 01. Introduction

#### Introduction

- 00:00:00 - 00:07:49

- ThePrimeagen introduces the course by discussing some personal background with algorithms, types of algorithms that will be covered, and suggestions for retaining the information presented in this course. Reasons to learn algorithms, why this course uses TypeScript, and ThePrimeagen's social media links are also provided in this lesson.

---

### 02. Basics

- Section Duration: 29 minutes

#### Big O Time Complexity

- 00:07:50 - 00:20:31

- ThePrimeagen discusses an overview of Big O, including, what it is, why it's used, and some essential concepts. A walkthrough of a Big O code example is also provided in this segment.

#### Arrays Data Structure

- 00:20:32 - 00:33:59

- ThePrimeagen demonstrates interpreting arrays as a fixed size, contiguous memory chunk by walking through array positions in an array buffer. Operations that can be performed on an array are also demonstrated in this segment.

#### Arrays Q&A

- 00:34:00 - 00:37:18

- ThePrimeagen answers student questions about whether there is no insert, push, or pop in an array and if an array's size and memory allocation must be specified at initialization. Questions regarding whether something that has an array is being created when creating an array in JavaScript and how big the array is that is instantiated are also covered in this segment.

---

### 03. Search

- Section Duration: 39 minutes

#### Linear Search & Kata Setup

- 00:37:19 - 00:44:38
- ThePrimeagen discusses searching through an array with a linear search algorithm. Setting up the TypeScript library Kata and a walkthrough of implementing the linear search algorithm are also covered in this segment.

#### Binary Search Algorithm

- 00:44:39 - 00:52:51
- ThePrimeagen demonstrates a search algorithm that jumps forward by ten percent, discusses possible pitfalls of that search, and demonstrates how the binary search algorithm differs. Binary search is an efficient algorithm for finding an item from a sorted list of items.

#### Pseudo Code Binary Search

- 00:52:52 - 00:59:12
- ThePrimeagen walks through creating and implementing a pseudo-code version of a Binary search algorithm.

#### Implementing Binary Search

- 00:59:13 - 01:03:52
- ThePrimeagen demonstrates implementing the binary search algorithm in TypeScript and uses the kata machine to test that the algorithm is correct. The binary search algorithm repeatedly halves the portion of a sorted list that could contain the target item until the possible locations have been narrowed down to one.

#### Two Crystal Balls Problem

- 01:03:53 - 01:09:38
- ThePrimeagen discusses options for solving this previous interview problem: When given two crystal balls that will break if dropped from a high enough distance, determine the exact spot in which it will break in the most optimized way. This segment demonstrates breaking down a search problem without using a linear search.

#### Implementing Two Crystal Balls

- 01:09:39 - 01:16:37
- ThePrimeagen walks through implementing the solution for the two crystal balls problem. Student questions regarding traveling using the cube root of N are also covered in this segment.

---

### 04. Sort

- Section Duration: 1 hour, 6 minutes

#### Bubble Sort

- 01:16:38 - 01:25:18
- ThePrimeagen demonstrates what happens under the hood when bubble sorting. Bubble sort repeatedly steps through the input list, swapping their values if needed until no swaps have to be performed during a pass, meaning that the list has become fully sorted.

#### Implementing Bubble Sort

- 01:25:19 - 01:34:44
- ThePrimeagen walks through implementing and testing the bubble sort algorithm. Student questions regarding how the formula was produced and for sorting algorithm suggestions for immutable arrays are also covered in this segment.

#### Linked List Data Structures

- 01:34:45 - 01:49:31
- ThePrimeagen discusses an overview of linked list data structures, including implementing deletion and insertion. A student's question regarding if there is no index in the linked list is also covered in this segment.

#### Linked List Complexity

- 01:49:32 - 01:54:28
- ThePrimeagen discusses the time and space complexity of linked lists. A student's question regarding the insertion of F is also covered in this segment.

#### Queue

- 01:54:29 - 02:00:18
- ThePrimeagen discusses the function of a queue, a linear data structure that follows the First in, First Out Principle (FIFO). Queue supports operations such as peek, enqueue, dequeue and print().

#### Implementing a Queue

- 02:00:19 - 02:07:40
- ThePrimeagen walks through implementing and testing the queue algorithm.

#### Queue Q&A

- 02:07:41 - 02:11:10
- ThePrimeagen answers student questions regarding if having no tail means there is no node, clarification on the peek method, and why this.tail.next is being set to the new node.

#### Stack

- 02:11:11 - 02:15:53
- ThePrimeagen demonstrates a linear data structure that follows the principle of Last In First Out, the opposite of a queue, a stack. In a stack, the last element inserted inside the stack is removed first.

#### Implementing a Stack

- 02:15:54 - 02:23:45
- ThePrimeagen walks through implementing and testing a stack, including push, pop, and peek.

---

### 05. Arrays

- Section Duration: 39 minutes

#### Arrays vs Linked List

- 02:23:46 - 02:29:54
- ThePrimeagen discusses similarities and differences between arrays and linked lists. Linked lists use less memory, but must be stepped through to find the target item. A demonstration of traversing a linked list is also provided in this segment.

#### ArrayList

- 02:29:55 - 02:41:40
- ThePrimeagen demonstrates the ability to write list operations such as get, push, and pop on arrays using ArrayList.

#### RingBuffer

- 02:41:41 - 02:48:41
- ThePrimeagen discusses an RingBuffer object which is used to represent a generic, fixed-length raw binary data buffer.

#### Data Structures Q&A

- 02:48:42 - 03:03:30
- ThePrimegen walks through an empirical test for what data structure is being used under the hood with `const a = []`. Student questions regarding if unshift and shift are exponential, what type of operation is slice, and where would this be used in practical code are also covered in this segment.

---

### 06. Recursion

- Section Duration: 47 minutes

#### Recursion

- 03:03:31 - 03:16:52
- ThePrimeagen discusses recursion as a function that calls itself until it reaches the base case and the problem is solved. Recursion can be broken into three steps: pre, recurse, and post.

#### Path Finding: Base Case

- 03:16:53 - 03:29:25
- ThePrimeagen walks through an example of pathfinding using a base case by implementing and testing the MazeSolver example in the kata machine.

#### Path Finding: Recursive Case

- 03:29:26 - 03:41:44
- ThePrimeagen walks through the MazeSolver example of pathfinding using the recursive case.

#### Recursion Q&A

- 03:41:45 - 03:50:57
- ThePrimeagen answers student questions regarding what happens when the recursive function can no longer move forward, how the end path of the MazeSolver was found, and if there are any scenarios in which changing the recursion direction would improve performance.

---

### 07. Quick Sort

- Section Duration: 29 minutes

#### QuickSort Algorithm

- 03:50:58 - 04:04:45
- ThePrimeagen discusses the QuickSort algorithm as an algorithm that uses a divide and conquer technique. The algorithm picks a pivot element and rearranges the array so elements smaller than the pivot element move to the left side of the pivot, and elements greater move to the right side. The algorithm then recursively sorts the subarrays on the left and right of the pivot element.

#### Implementing QuickSort

- 04:04:46 - 04:20:42
- ThePrimeagen walks through implementing and testing the QuickSort algorithm in the kata machine. Both a Quicksort function and a partition function are implemented in this segment.

---

### 08. Doubly Linked List

- Section Duration: 35 minutes

#### Linked List: prepend, insertAt, & append

- 04:20:43 - 04:33:20
- ThePrimeagen walks through implementing a doubly linked list, including prepend, insertAt, and append.

#### Linked List: remove, get, & removeAt

- 04:33:21 - 04:46:34
- ThePrimeagen walks through implementing the second half of a doubly linked list, including remove, get, and removeAt.

#### Linked List Q&A

- 04:46:35 - 04:50:38
- ThePrimeagen answers student questions regarding using VIM, if setting remove undefined would break, where the methods are taken from, and the reason for using the Java methods.

#### Debugging Linked List

- 04:50:39 - 04:56:38
- ThePrimeagen walks through debugging the remove portion of the doubly linked list. A student's question regarding an example of keeping track of removed nodes is also covered in this segment.

---

### 09. Trees

- Section Duration: 32 minutes

#### Trees Overview

- 04:56:39 - 05:04:34
- ThePrimeagen discusses an overview of more advanced data structures known as trees and walks through some terminology with a whiteboard example. A tree can be empty with no nodes, or a tree can be a structure consisting of one node called the root and zero or one or more subtrees.

#### Tree Traversals

- 05:04:35 - 05:14:01
- ThePrimeagen discusses and demonstrates, via whiteboarding, visiting nodes using three types of traversals preorder, inorder, and postorder.

#### Implement Tree Traversal

- 05:14:02 - 05:29:00
- ThePrimeagen live codes the three types of tree traversals. Inorder traversal traverses one subtree of a node, visits the node, and then traverses its other subtree. Preorder traversal visits a node and then traverses both of its subtrees. Postorder traversal traverses both subtrees of a node, then visits the node.

---

### 10. Tree Search

- Section Duration: 1 hour

#### Breadth-First Search

- 05:29:01 - 05:35:24
- ThePrimeagen discusses using a queue data structure to perform a breadth-first search and the running time.

#### Implement Breadth-First Search

- 05:35:25 - 05:43:02
- ThePrimeagen walks through implementing a breadth-first search on a binary tree by pushing into a queue instead of recursing. A brief discussion regarding student preferences between breadth-first and depth-first searches is also covered in this segment.

#### Search Practice

- 05:43:03 - 05:47:23
- ThePrimeagen walks through an interview question example of comparing the contents and shape. Depth-first search preserves tree shape, while breadth-first search does not.

#### Implement Binary Tree Comparison

- 05:47:24 - 05:55:29
- ThePrimeagen walks through implementing breadth-first and depth-first searching to compare two binary trees and testing the resulting functions using the kata machine.

#### Depth-First: Find

- 05:55:30 - 06:05:20
- ThePrimeagen discusses quick finding using a binary search tree. Students' questions regarding possible use cases and if the right side can be greater than the initial node or if it has to be equal are also covered in this segment.

#### Depth-First: Insert

- 06:05:21 - 06:13:20
- ThePrimeagen writes out pseudo-code to demonstrate insertion in a binary tree and demonstrates what to do in a null case.

#### Depth-First: Delete

- 06:13:21 - 06:20:13
- ThePrimeagen discusses deletion cases in a depth-first binary tree, including, no child and one child while smallest on the large side and largest on the small side can be reduced to no child and one child deletion.

#### Binary Search Tree Q&A

- 06:20:14 - 06:24:20
- ThePrimeagen answers student questions regarding if the tree will be balanced after insertion, AVL compared to red black, if removing the same node can result in different trees, and if there are other ways to make trees.

#### Implement Depth-First Search

- 06:24:21 - 06:29:12
- ThePrimeagen walks through implementing and testing a depth-first binary search.

---

### 11. Heap

- Section Duration: 49 minutes

#### Heap

- 06:29:13 - 06:45:03
- ThePrimeagen discusses the heap data structure as a binary tree where every child and grandchild is smaller (MinHeap) or larger than (MaxHeap) the current node. Student questions regarding if this is considered a doubly linked list and if this is implemented in an array are also covered in this segment.

#### Implementing Heap

- 06:45:04 - 07:04:11
- ThePrimeagen walks through implementing and testing a MinHeap data structure using a JavaScript array in the kata machine. The insert and delete methods are implemented in this segment.

#### Tries

- 07:04:12 - 07:18:39
- ThePrimeagen discusses visualizing tries as autocomplete, demonstrates the structure of a trie tree with pseudo code, and implements a trie tree in the kata machine. Insertion and deletion in a trie tree are also covered in this segment.

---

### 12. Graphs

- Section Duration: 1 hour, 14 minutes

#### Graphs Overview

- 07:18:40 - 07:26:11
- ThePrimeagen discusses an overview of graphs as a series of nodes with connections and terminology related to graphs. Vocabulary covered in this segment includes cycle, acyclic, connected, directed, undirected, weighted, dag, node, and edge.

#### Searching an Adjacency Matrix

- 07:26:12 - 07:39:19
- ThePrimeagen demonstrates representing graphs in an adjacency matrix. Breadth-first and depth-first searches still exist on a graph, and are virtually the same as on a tree.

#### Implementing BFS on Adjacency Matrix

- 07:39:20 - 07:47:48
- ThePrimeagen walks through implementing and testing a breadth-first search on an adjacency matrix using the kata machine. An adjacency Matrix is a 2D array of size V x V where V is the number of vertices in a graph.

#### Implement DFS on Adjacency List

- 07:47:49 - 07:59:23
- ThePrimeagen walks through implementing and testing a depth-first search on an adjacency list using the kata machine. An Adjacency list is an array consisting of the address of all the linked lists.

#### Dijkstra's Shortest Path

- 07:59:24 - 08:11:58
- ThePrimeagen discusses Dijkstra's shortest path, what it is, where it's used, and demonstrates some variations of it. Dijkstra's shortest path is an algorithm that finds the shortest paths between nodes in a graph.

#### Implement Dijkstra's Shortest Path

- 08:11:59 - 08:24:02
- ThePrimeagen walks through implementing and testing a version of Dijkstra's shortest path in the kata machine.

#### Dijkstra's Shortest Path Run Time

- 08:24:03 - 08:33:21
- ThePrimeagen discusses the running time of Dijkstra's shortest path by walking through what happens behind the scenes in pseudo-code. A student's question regarding if there are a lot of graph questions in interviews is also covered in this segment.

---

### 13. Maps & LRU

- Section Duration: 44 minutes

#### Maps

- 08:33:22 - 08:45:03
- ThePrimeagen discusses an overview of map terminology, including load factor, key-value, and collision.

#### LRU Cache

- 08:45:04 - 08:55:41
- ThePrimeagen discusses a least recently used cache data structure that evicts the least recently used item. An LRU cache is a combination of map and linked list data structures.

#### LRU Cache Setup

- 08:55:42 - 08:59:18
- ThePrimeagen walks through setting up a pseudocode outline for the LRU cache data structure.

#### Implementing an LRU Cache

- 08:59:19 - 09:17:50
- ThePrimeagen walks through implementing and testing an LRU cache in the kata machine.

---

### 14. Wrapping Up

- Section Duration: 3 minutes

#### Wrapping Up

- 09:17:51 - 09:21:18
- ThePrimeagen wraps up the course by providing a brief overview of the material covered and directions on what to look into next. Heartfelt well wishes and encouragement to utilize opportunities given are also provided in this segment.
