# Full-Length Mock Test 3 (100 MCQs)

Mixed subjects:
- Programming Fundamentals
- Object-Oriented Programming
- Data Structures & Algorithms
- Databases
- Operating Systems
- Discrete Structures
- Artificial Intelligence
- Theory of Automata
- Software Engineering
- Computer Networks

## Instructions

- 100 MCQs, single-best-answer
- No negative marking assumed
- Time yourself to simulate the real exam
- Mark uncertain questions for a second pass

---

## Questions 1–25

1. In C-like languages, which of the following expressions is most likely to cause undefined behavior?  
   A. `x = y + 1;`  
   B. `int a[5]; a[4] = 10;`  
   C. `int i = 0; i = ++i + i++;`  
   D. `if (x > 0) x--;`  

2. Which OOP principle primarily supports changing the internal representation without changing external code?  
   A. Inheritance  
   B. Polymorphism  
   C. Encapsulation  
   D. Overloading  

3. Average-case time complexity of inserting into a balanced BST with `n` nodes is:  
   A. `O(1)`  
   B. `O(log n)`  
   C. `O(n)`  
   D. `O(n log n)`  

4. In the relational model, which key is chosen from candidate keys to act as the main identifier?  
   A. Super key  
   B. Primary key  
   C. Alternate key  
   D. Foreign key  

5. In OS, response time is defined as:  
   A. Time from submission to completion  
   B. Time in ready queue  
   C. Time from submission until first response  
   D. CPU time used  

6. A relation R on set A is reflexive if:  
   A. Every element is related to itself  
   B. Whenever aRb then bRa  
   C. Whenever aRb and bRc then aRc  
   D. Whenever aRb and bRa then a=b  

7. Which search algorithm is guaranteed optimal when all step costs are equal and branching factor is finite?  
   A. DFS  
   B. BFS  
   C. Greedy Best-First Search  
   D. Hill Climbing  

8. The language `{ a^n b^n | n ≥ 0 }` is:  
   A. Regular  
   B. Context-free but not regular  
   C. Not context-free  
   D. Finite  

9. In automata theory, which pair of models has exactly the same expressive power?  
   A. DFA and PDA  
   B. NFA and DFA  
   C. PDA and TM  
   D. DFA and TM  

10. Which process model emphasizes working software in short iterations and customer feedback?  
    A. Waterfall  
    B. V-model  
    C. Spiral  
    D. Agile (e.g., Scrum)  

11. Which protocol is used to transfer hypertext documents over an insecure connection?  
    A. HTTP  
    B. HTTPS  
    C. FTP  
    D. SMTP  

12. In C-like languages, what does `++i` return?  
    A. Old value of i, then increments  
    B. New value of i after increment  
    C. Always 1  
    D. Depends only on compiler flag  

13. Overriding in a language like C++ is associated primarily with:  
    A. Static binding  
    B. Dynamic dispatch via virtual functions  
    C. Function templates  
    D. Macros  

14. Time complexity of selection sort on an array of size `n` is:  
    A. `O(n)`  
    B. `O(n log n)`  
    C. `O(n^2)`  
    D. `O(log n)`  

15. Which normal form requires that every determinant is a candidate key?  
    A. 1NF  
    B. 2NF  
    C. 3NF  
    D. BCNF  

16. In OS, which scheduling algorithm assigns CPU to the process with the smallest CPU burst time?  
    A. FCFS  
    B. SJF  
    C. RR  
    D. Priority without preemption  

17. A function `f: A → B` is surjective (onto) if:  
    A. Each element of A maps to a unique element of B  
    B. Every element of B has at least one preimage in A  
    C. A and B are finite  
    D. It has an inverse function  

18. In AI, which search strategy uses the evaluation function `f(n) = h(n)`?  
    A. Uniform Cost Search  
    B. BFS  
    C. Greedy Best-First Search  
    D. A*  

19. The pumping lemma for regular languages provides:  
    A. A necessary condition for regularity  
    B. A sufficient condition for regularity  
    C. Always both necessary and sufficient condition  
    D. A way to construct minimal DFA  

20. Which network device reduces collision domains by forwarding based on MAC addresses?  
    A. Hub  
    B. Switch  
    C. Repeater  
    D. Router  

21. In C/C++, what is the typical behavior of reading from an uninitialized local variable?  
    A. Reads zero  
    B. Reads null  
    C. Reads an indeterminate/garbage value  
    D. Causes compile-time error  

22. Inheritance is best used to model:  
    A. “has-a” relationships  
    B. “is-a” relationships  
    C. “uses-a” relationships  
    D. “part-of” relationships  

23. For a graph represented using adjacency matrix, checking existence of an edge (u,v) takes:  
    A. `O(1)` time  
    B. `O(log n)` time  
    C. `O(n)` time  
    D. `O(E)` time  

24. In SQL, which statement will remove all rows from table T but preserve its structure and definition?  
    A. DROP TABLE T;  
    B. DELETE FROM T;  
    C. TRUNCATE TABLE T;  
    D. ALTER TABLE T;  

25. Which page replacement algorithm uses a circular list and a reference bit to approximate LRU?  
    A. FIFO  
    B. Optimal  
    C. Clock (Second-Chance)  
    D. Random  

---

## Questions 26–50

26. A simple undirected graph is called complete if:  
    A. It has no edges  
    B. It has exactly n-1 edges  
    C. Every pair of distinct vertices is connected by an edge  
    D. It contains exactly one cycle  

27. Number of permutations of `n` distinct elements taken `n` at a time is:  
    A. `n`  
    B. `n^2`  
    C. `n!`  
    D. `2^n`  

28. In AI, BFS is guaranteed to be complete if:  
    A. Branching factor is finite and any solution is at finite depth  
    B. Heuristic is admissible  
    C. Heuristic is consistent  
    D. Path cost is always zero  

29. The language `{ 0^n 1^n | n ≥ 0 }` can be recognized by:  
    A. DFA only  
    B. NFA only  
    C. PDA  
    D. Finite automaton with two tapes only  

30. Which process model is most suitable for high-risk, large projects where risk analysis is critical?  
    A. Waterfall  
    B. Spiral  
    C. Agile Kanban  
    D. Prototyping only  

31. DHCP’s primary function is to:  
    A. Map IP to MAC  
    B. Map hostname to IP  
    C. Dynamically allocate IP configuration  
    D. Encrypt network traffic  

32. In C-like languages, which type can hold fractional values?  
    A. int  
    B. short  
    C. float  
    D. char  

33. In OOP, which is true for an abstract class?  
    A. It cannot contain any concrete methods  
    B. It cannot be a base class  
    C. It cannot be instantiated directly  
    D. It must contain only static methods  

34. The time complexity of Dijkstra’s algorithm with adjacency list and binary heap is:  
    A. `O(V + E)`  
    B. `O((V+E) log V)`  
    C. `O(V^2)`  
    D. `O(E^2)`  

35. In SQL, which command is used to add a new column to an existing table?  
    A. ALTER TABLE  
    B. UPDATE TABLE  
    C. MODIFY TABLE  
    D. APPEND TABLE  

36. In OS, internal fragmentation is:  
    A. Wasted space inside allocated blocks  
    B. Wasted space between allocated blocks  
    C. Wasted space in swap area only  
    D. Impossible when using paging  

37. The degree of a vertex in a simple undirected graph is:  
    A. Number of vertices reachable from it  
    B. Number of edges incident to it  
    C. Number of self-loops  
    D. Number of connected components  

38. A heuristic h is admissible if:  
    A. It never underestimates  
    B. It never overestimates true cost to goal  
    C. It always equals true cost  
    D. It ignores goal costs  

39. Which language is regular?  
    A. `{ a^n b^n | n ≥ 0 }`  
    B. `{ a^n | n is prime }`  
    C. `{ w ∈ {0,1}* | w has exactly 3 ones }`  
    D. `{ a^n b^n c^n | n ≥ 0 }`  

40. Integration testing primarily verifies:  
    A. Individual functions  
    B. User interface design  
    C. Interactions between modules  
    D. Database schema correctness only  

41. The protocol used at transport layer that is connection-oriented and reliable is:  
    A. TCP  
    B. UDP  
    C. IP  
    D. ARP  

42. In C/C++, the expression `a & b` (bitwise AND) differs from `a && b` (logical AND) because:  
    A. `&` short-circuits, `&&` does not  
    B. `&&` short-circuits, `&` does not  
    C. They are identical  
    D. Both are bitwise  

43. A binary tree of height h (root at height 0) has at most how many nodes?  
    A. `2^h`  
    B. `2^(h+1) - 1`  
    C. `h^2`  
    D. `h!`  

44. In 3NF, for every functional dependency X → Y, one of the requirements is:  
    A. X is a super key or Y is prime (part of a key)  
    B. Y is always a key  
    C. X and Y are disjoint sets  
    D. No foreign keys exist  

45. Deadlock detection involves:  
    A. Preventing at least one necessary condition  
    B. Periodically checking resource-allocation graph for cycles  
    C. Ignoring resource allocation  
    D. Using only FCFS  

46. The handshaking lemma in graph theory states that:  
    A. Sum of degrees = number of edges  
    B. Sum of degrees = 2 × number of edges  
    C. Number of edges = number of vertices  
    D. Degrees are always even  

47. In AI, hill-climbing search can:  
    A. Guarantee global optimum  
    B. Get stuck in local maxima  
    C. Always find shortest path  
    D. Avoid plateaus automatically  

48. A right-linear grammar generates exactly:  
    A. Regular languages  
    B. Context-free languages  
    C. Context-sensitive languages  
    D. Decidable languages  

49. Regression testing is primarily intended to:  
    A. Check performance under heavy load  
    B. Ensure recent changes didn’t break previous functionality  
    C. Minimize code size  
    D. Validate hardware compatibility  

50. In the TCP/IP model, the Internet layer corresponds roughly to which OSI layer?  
    A. Application  
    B. Session  
    C. Network  
    D. Data Link  

---

## Questions 51–75

51. In C, the expression `(a = 5)` used in a condition:  
    A. Is illegal  
    B. Always evaluates to 0  
    C. Evaluates to 5 (true)  
    D. Causes compile-time error  

52. OOP polymorphism allows:  
    A. Multiple functions with same name and different signatures  
    B. Different classes to be used interchangeably via a common interface  
    C. Only operator overloading  
    D. Only use of templates  

53. For a sparse graph (few edges), which representation is more space-efficient?  
    A. Adjacency matrix  
    B. Adjacency list  
    C. Incidence matrix always  
    D. Both equal  

54. In SQL, `HAVING` clause is applied:  
    A. Before `GROUP BY`  
    B. After `GROUP BY` to filter groups  
    C. Instead of `WHERE` always  
    D. Only to remove duplicates  

55. Paging eliminates:  
    A. Internal fragmentation  
    B. External fragmentation  
    C. Both internal and external fragmentation  
    D. Need for a page table  

56. Number of subsets of a set with 7 elements is:  
    A. 7  
    B. 49  
    C. 64  
    D. 128  

57. For A* search with a consistent heuristic:  
    A. Once a node is expanded, its best path cost is known  
    B. Nodes must be reopened frequently  
    C. Search is incomplete  
    D. Heuristic must equal true cost  

58. The language `{ w ∈ {a,b}* | w is palindrome }` is:  
    A. Regular  
    B. CFL but not regular  
    C. Not CFL  
    D. Finite  

59. Adaptive maintenance is done to:  
    A. Add features  
    B. Fix bugs  
    C. Adapt to environment changes (OS, hardware, regulations)  
    D. Improve maintainability only  

60. SMTP is primarily used to:  
    A. Fetch emails from server  
    B. Send emails between mail servers or client to server  
    C. Transfer files  
    D. Resolve hostnames  

61. In C, which construct allows multiple branches based on constant integral values?  
    A. if-else-if ladder  
    B. switch  
    C. while  
    D. for  

62. A stack is best suited for:  
    A. FIFO scheduling  
    B. Implementation of recursion and undo operations  
    C. Priority scheduling  
    D. Hash indexing  

63. A graph is bipartite if:  
    A. Its vertices can be partitioned into two sets with no edges inside each set  
    B. It has no cycles  
    C. It has exactly one cycle  
    D. It is complete  

64. BCNF is:  
    A. Same as 3NF  
    B. Strictly weaker than 3NF  
    C. Strictly stronger (stricter) than 3NF  
    D. Unrelated to 3NF  

65. Deadlock prevention by resource ordering typically breaks which condition?  
    A. Mutual exclusion  
    B. Hold and wait  
    C. No preemption  
    D. Circular wait  

66. In propositional logic, a tautology is:  
    A. False under at least one assignment  
    B. True under all assignments  
    C. Neither true nor false  
    D. True only for some assignments  

67. A PDA with a stack of unbounded size recognizes:  
    A. Regular languages  
    B. Context-free languages  
    C. Context-sensitive languages  
    D. Recursive languages  

68. System testing focuses on:  
    A. Individual units  
    B. Integrated system as a whole against requirements  
    C. Only performance  
    D. Only database integrity  

69. ARP is used to:  
    A. Map domain names to IP  
    B. Map IP to MAC on local network  
    C. Allocate IP addresses  
    D. Encrypt payload  

70. Which of the following C operations can easily cause buffer overflow if not used carefully?  
    A. `strcpy`  
    B. `strlen`  
    C. `strcmp`  
    D. `sizeof`  

71. BFS uses which data structure for frontier?  
    A. Stack  
    B. Queue  
    C. Priority queue  
    D. Deque only  

72. A FULL OUTER JOIN between tables A and B returns:  
    A. Only matches  
    B. All rows from A and B, with NULLs for missing matches  
    C. Only rows from A  
    D. Only rows from B  

73. Starvation is best described as:  
    A. Permanent blocking of a process that never gets resources  
    B. A cyclic wait among processes  
    C. Excessive page faults  
    D. Long I/O burst  

74. DFA differ from NFA in that DFA:  
    A. Are more powerful  
    B. Have at most one transition per symbol from each state  
    C. Require epsilon-moves  
    D. Cannot accept finite languages  

75. Load testing mainly aims to:  
    A. Find logical bugs  
    B. Determine system behavior under expected or heavy loads  
    C. Validate UI design  
    D. Replace unit testing  

---

## Questions 76–100

76. `C(5,2)` equals:  
    A. 5  
    B. 10  
    C. 20  
    D. 25  

77. DFS on an infinite tree without limit or visited set:  
    A. Is always complete  
    B. May never reach shallow solutions  
    C. Always finds optimal path  
    D. Is identical to BFS  

78. Recursively enumerable languages (RE) are:  
    A. Accepted by some Turing machine that may not halt for non-members  
    B. Decidable languages  
    C. Regular languages only  
    D. CFLs only  

79. High cohesion means:  
    A. Module has loosely related tasks  
    B. Module’s responsibilities are strongly related  
    C. Module interfaces are complex  
    D. Module uses many global variables  

80. In TCP, congestion control is primarily concerned with:  
    A. Preventing receiver buffer overflow  
    B. Preventing network congestion collapse  
    C. Mapping ports  
    D. Resolving hostnames  

81. In C, integer expression `8 / 3 * 3` evaluates to:  
    A. 8  
    B. 9  
    C. 6  
    D. 7  

82. Height of a complete binary tree with `n` nodes is approximately:  
    A. `log2 n`  
    B. `n`  
    C. `n log n`  
    D. `sqrt(n)`  

83. 3NF addresses which kind of dependency beyond 2NF?  
    A. Multivalued  
    B. Transitive dependency of non-key on non-key  
    C. Functional dependency on super key  
    D. Partial dependency  

84. A context switch typically saves and restores:  
    A. Only program counter  
    B. PCB: registers, PC, state, etc.  
    C. Entire RAM  
    D. Disk contents  

85. Mathematical induction on natural numbers has two main steps:  
    A. Base case + inductive step  
    B. Base case + contradiction  
    C. Contrapositive + case analysis  
    D. Example + experiment  

86. `{ a^n b^n c^n | n ≥ 0 }` is:  
    A. Regular  
    B. Context-free  
    C. Not context-free  
    D. Finite  

87. Black-box testing mainly looks at:  
    A. Internal code structure  
    B. Input-output behavior, ignoring internal structure  
    C. Memory layout  
    D. CPU utilization  

88. UDP is suitable when:  
    A. You require strict in-order reliable delivery  
    B. Some packet loss is acceptable and low latency is critical  
    C. You send large files reliably  
    D. You need built-in security  

89. In C, `register` keyword historically suggests:  
    A. Variable must be global  
    B. Compiler may store variable in CPU register  
    C. Variable is constant  
    D. Variable is on disk  

90. Prim’s and Kruskal’s algorithms both compute:  
    A. Shortest paths  
    B. Minimum spanning trees  
    C. Topological order  
    D. Strongly connected components  

91. Regular languages are closed under:  
    A. Union  
    B. Concatenation  
    C. Kleene star  
    D. All of the above  

92. Acceptance testing is primarily for:  
    A. Developer internal checks  
    B. Customer/user validation of requirements  
    C. Unit-level structural validation  
    D. Compiler correctness  

93. Router operates mainly at OSI layer:  
    A. 2  
    B. 3  
    C. 4  
    D. 7  

94. Starvation can often be reduced by:  
    A. Using non-preemptive scheduling  
    B. Aging: gradually increasing waiting process priority  
    C. Decreasing time quantum  
    D. Ignoring low-priority tasks  

95. A tree is:  
    A. Disconnected graph  
    B. Connected graph with exactly one simple path between any pair of vertices  
    C. Graph with one cycle  
    D. Complete graph  

96. Turing machines are more powerful than PDA because:  
    A. They are deterministic  
    B. They have an unbounded tape and can simulate arbitrary memory  
    C. They run faster  
    D. They use fewer states  

97. A non-functional requirement example is:  
    A. “System shall allow user to change password”  
    B. “System shall calculate GPA”  
    C. “System shall have 99.5% availability”  
    D. “System shall send reminder emails”  

98. DNS primarily maps:  
    A. IP to MAC  
    B. Hostname to IP  
    C. MAC to IP  
    D. Email address to IP  

99. A regular language example over `{a}` is:  
    A. `{ a^n | n is prime }`  
    B. `{ a^n | n ≥ 0 }`  
    C. `{ a^n b^n | n ≥ 0 }`  
    D. `{ a^n b^n c^n | n ≥ 0 }`  

100. In a no-negative-marking MCQ exam, once you have eliminated at least one option, the rational strategy is to:  
     A. Leave the question blank  
     B. Guess among remaining options  
     C. Answer only if sure  
     D. Skip all hard questions  

---

## Answer Key – Mock Test 3

| Q | Ans | Q | Ans | Q | Ans | Q | Ans |
|---|---|---|---|---|---|---|---|
| 1 | C | 26 | C | 51 | C | 76 | B |
| 2 | C | 27 | C | 52 | B | 77 | B |
| 3 | B | 28 | A | 53 | B | 78 | A |
| 4 | B | 29 | C | 54 | B | 79 | B |
| 5 | C | 30 | B | 55 | B | 80 | B |
| 6 | A | 31 | C | 56 | D | 81 | C |
| 7 | B | 32 | C | 57 | A | 82 | A |
| 8 | B | 33 | C | 58 | B | 83 | B |
| 9 | B | 34 | B | 59 | C | 84 | B |
|10 | D | 35 | A | 60 | B | 85 | A |
|11 | A | 36 | A | 61 | B | 86 | C |
|12 | B | 37 | B | 62 | B | 87 | B |
|13 | B | 38 | B | 63 | A | 88 | B |
|14 | C | 39 | C | 64 | C | 89 | B |
|15 | D | 40 | C | 65 | D | 90 | B |
|16 | B | 41 | A | 66 | B | 91 | D |
|17 | B | 42 | B | 67 | B | 92 | B |
|18 | C | 43 | B | 68 | B | 93 | B |
|19 | A | 44 | A | 69 | B | 94 | B |
|20 | B | 45 | B | 70 | A | 95 | B |
|21 | C | 46 | B | 71 | B | 96 | B |
|22 | B | 47 | B | 72 | B | 97 | C |
|23 | A | 48 | A | 73 | A | 98 | B |
|24 | C | 49 | B | 74 | B | 99 | B |
|25 | C | 50 | C | 75 | B |100 | B |

### High-Value Trap Notes (Selected)

- Q1, Q12, Q21, Q31, Q51, Q70, Q81: Subtle C/C++ behavior (undefined behavior, assignments in conditions, short-circuit vs bitwise).  
- Q8, Q9, Q19, Q29, Q39, Q48, Q58, Q67, Q74, Q78, Q86, Q91, Q99: Language class classification (regular/CFL/non-CFL/RE) and automata–grammar equivalences.  
- Q25, Q36, Q55, Q83: Paging, internal fragmentation, and normal forms (2NF/3NF/BCNF) are common conceptual MCQ sources.  
- Q35, Q44, Q64: SQL DDL/DML and normalization dependencies are often asked in disguised forms.  
- Q73, Q94: Starvation vs deadlock and aging vs other policies are classical OS traps.  
- Q100: As always with no negative marking, elimination followed by a calculated guess is mathematically superior to leaving answers blank.
