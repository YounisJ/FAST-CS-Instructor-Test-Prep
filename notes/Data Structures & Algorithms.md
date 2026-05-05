## Data Structures & Algorithms

### High-Yield Topics

- Asymptotic notation: Big-O, Big-Omega, Big-Theta
- Arrays, linked lists, stacks, queues, deques
- Trees: BST, AVL, heap, B-tree, B+ tree basics
- Hashing: collisions, chaining, open addressing, load factor
- Graphs: BFS, DFS, topological sort, shortest path, MST
- Recursion, divide and conquer, greedy basics, dynamic programming intuition
- Sorting and searching complexities

### Revision Notes

#### Core Definitions

| Term | Meaning |
|---|---|
| Big-O | Upper bound on growth |
| Big-Omega | Lower bound on growth |
| Big-Theta | Tight bound on growth |
| Stable sort | Preserves relative order of equal keys |
| In-place algorithm | Uses small extra memory beyond input |
| Heap | Complete binary tree with heap-order property |

#### Core Complexity Table

| Operation / Algorithm | Typical Complexity | Notes |
|---|---|---|
| Linear search | O(n) | Works on unsorted data |
| Binary search | O(log n) | Requires sorted structure |
| Insertion sort | O(n^2) | Efficient for nearly sorted small input |
| Merge sort | O(n log n) | Stable, not in-place in standard array form |
| Heap sort | O(n log n) | In-place, not stable |
| Quick sort | Avg O(n log n), worst O(n^2) | Pivot choice matters |
| BFS / DFS | O(V + E) | Adjacency-list representation |
| Hash search | Avg O(1) | Worst-case can degrade |

#### High-Yield Comparisons

| Concept A | Concept B | Difference |
|---|---|---|
| Stack | Queue | LIFO vs FIFO |
| BST | Heap | Ordered search tree vs priority structure |
| BFS | DFS | Level-wise vs depth-first exploration |
| Merge sort | Quick sort | Stable predictable vs pivot-sensitive |
| B-tree | B+ tree | Data in internal and leaf nodes vs leaf-focused records |

> Common trap: Binary search is only valid when the search space is ordered and the invariant is maintained correctly.

#### Memory Tricks

- BFS uses queue, DFS uses stack or recursion
- Heap gives fastest access to min/max, not arbitrary search
- Stable sort keeps equal elements in original order
- Hashing average case is great, worst case is not

### Practice MCQs

#### MCQ 1

Which data structure directly supports FIFO behavior?

A. Stack  
B. Queue  
C. Heap  
D. BST

**Answer:** B  
**Explanation:** Queue removes elements in the order they were inserted.

#### MCQ 2

Which algorithm requires the input to be sorted for correctness?

A. DFS  
B. Linear search  
C. Binary search  
D. BFS

**Answer:** C  
**Explanation:** Binary search assumes ordered input to discard half the search space.

#### MCQ 3

Which of the following is true for a max-heap?

A. Inorder traversal gives sorted order  
B. Root contains minimum key  
C. Parent key is always greater than or equal to child keys  
D. It is always a BST

**Answer:** C  
**Explanation:** A max-heap maintains parent >= children, but it is not a BST.

#### MCQ 4

Average-case time complexity of searching in a hash table with a good hash function is closest to:

A. O(1)  
B. O(log n)  
C. O(n)  
D. O(n log n)

**Answer:** A  
**Explanation:** Under good distribution and moderate load, hash table operations are constant on average.

#### MCQ 5

Which traversal of a BST produces keys in sorted order?

A. Preorder  
B. Postorder  
C. Inorder  
D. Level order

**Answer:** C  
**Explanation:** Inorder on BST visits left, root, right, yielding sorted sequence.

#### MCQ 6

Which statement about merge sort is correct?

A. It is always in-place on arrays  
B. It is unstable  
C. Its worst-case time is O(n log n)  
D. It requires sorted input

**Answer:** C  
**Explanation:** Merge sort guarantees O(n log n) time in the worst case.

#### MCQ 7

For a graph with weighted non-negative edges, the standard shortest path algorithm from one source is:

A. Prim  
B. Kruskal  
C. Dijkstra  
D. Floyd only

**Answer:** C  
**Explanation:** Dijkstra works correctly for non-negative edge weights.

#### MCQ 8

Which of the following most naturally uses recursion?

A. Array indexing  
B. Tree traversal  
C. Hash insertion  
D. Circular queue modulo arithmetic

**Answer:** B  
**Explanation:** Recursive definition maps naturally to hierarchical tree structure.

#### MCQ 9

A stable sorting algorithm is useful when:

A. The array is already reversed  
B. Equal keys carry secondary meaning from original order  
C. Only integers are present  
D. We need O(1) time sorting

**Answer:** B  
**Explanation:** Stability matters when earlier ordering should be preserved among ties.

#### MCQ 10

Topological sort is defined only for:

A. Undirected connected graphs  
B. Trees only  
C. Directed acyclic graphs  
D. Weighted graphs only

**Answer:** C  
**Explanation:** Cycles make a topological order impossible.

### Summary Sheet

- Memorize standard complexities and data-structure properties.
- Distinguish search structures from priority structures.
- Expect conceptual MCQs around invariants, edge cases, and trade-offs.
- Rehearse BFS, DFS, Dijkstra, heap, BST, hashing, and sorting differences.
