## Full-Length Mock Test 2 (100 MCQs)

This mock is designed as another 100-question, mixed-subject exam aligned with FAST BS CS core courses: Programming Fundamentals, OOP, Data Structures, Discrete Structures, Database Systems, Operating Systems, Theory of Automata, Artificial Intelligence, Computer Networks, and Software Engineering.[web:19]

### Instructions

- Total Questions: 100
- No negative marking assumed: attempt every question
- Difficulty: Medium to advanced
- Strategy: 
  - Pass 1: Solve high-confidence questions
  - Pass 2: Use elimination for remaining
  - Pass 3: Check wording traps (at least / at most / only if / exactly one)

---

## Mock Test 2 – Questions

### Questions 1–25

1. In C/C++-like languages, which of the following is most accurate about `char`?  
   A. It is always unsigned  
   B. It is always 16 bits  
   C. It is an integer type capable of storing small integers  
   D. It cannot participate in arithmetic  

2. Which OOP feature allows the same operation to behave differently on different classes?  
   A. Encapsulation  
   B. Polymorphism  
   C. Inheritance  
   D. Overloading only  

3. For a sorted array, the worst-case number of comparisons in binary search on `n` elements is proportional to:  
   A. `log n`  
   B. `n`  
   C. `sqrt(n)`  
   D. `n log n`  

4. In the relational model, a super key is:  
   A. Any attribute set that uniquely identifies tuples  
   B. A minimal unique attribute set  
   C. A foreign key in another relation  
   D. Always a single attribute  

5. Which OS concept allows multiple processes to share the CPU seemingly simultaneously?  
   A. Virtual memory only  
   B. Multiprogramming and time-sharing  
   C. Deadlock detection  
   D. DMA  

6. A relation R on set A is symmetric if:  
   A. For all a, aRa holds  
   B. For all a,b, if aRb then bRa  
   C. For all a,b,c, aRb and bRc imply aRc  
   D. For all a,b, if aRb and bRa then a=b  

7. Which search algorithm guarantees to find an optimal solution for positive costs if one exists and the heuristic is admissible?  
   A. Greedy Best-First Search  
   B. A* Search  
   C. Depth-First Search  
   D. Hill Climbing  

8. The language of all palindromes over `{a,b}` is:  
   A. Regular  
   B. Context-free but not regular  
   C. Not context-free  
   D. Finite  

9. In the Chomsky hierarchy, regular languages are:  
   A. Type 0  
   B. Type 1  
   C. Type 2  
   D. Type 3  

10. Which process model best supports highly iterative, feedback-driven development?  
    A. Waterfall  
    B. Spiral  
    C. Agile / incremental  
    D. V-model only  

11. Which protocol is typically used to retrieve web pages over an encrypted connection?  
    A. HTTP  
    B. FTP  
    C. HTTPS  
    D. SMTP  

12. What is the output of the following C-like code on a typical system?  
    ```c
    int x = 3;
    int y = x++ + ++x;
    printf("%d", y);
    ```  
    A. 7  
    B. 8  
    C. 9  
    D. Behavior is undefined  

13. Which OOP mechanism allows redefining a base class virtual function in a derived class?  
    A. Overloading  
    B. Overriding  
    C. Hiding via private inheritance  
    D. Friend function  

14. The worst-case time complexity of merge sort on `n` elements is:  
    A. `O(n)`  
    B. `O(n log n)`  
    C. `O(n^2)`  
    D. `O(log n)`  

15. A relation is in 1NF if:  
    A. Every non-key attribute is fully dependent on the key  
    B. Every non-key attribute is non-transitively dependent on the key  
    C. All values are atomic and there are no repeating groups  
    D. All determinants are candidate keys  

16. Which of the following is not a classical CPU scheduling criterion?  
    A. CPU utilization  
    B. Throughput  
    C. Turnaround time  
    D. Disk fragmentation rate  

17. A function `f: A → B` is bijective if:  
    A. It is injective but not surjective  
    B. It is surjective but not injective  
    C. It is both injective and surjective  
    D. Domain equals codomain regardless of mapping  

18. In AI, a heuristic `h1` is said to dominate `h2` if:  
    A. `h1(n) <= h2(n)` for all nodes and both admissible  
    B. `h1(n) >= h2(n)` for all nodes and both admissible  
    C. `h1(n)` is constant and `h2(n)` varies  
    D. `h1` is inconsistent but `h2` is not  

19. Which device primarily operates at the physical layer?  
    A. Router  
    B. Switch  
    C. Hub  
    D. Gateway  

20. Which machine model corresponds to context-sensitive languages in the Chomsky hierarchy?  
    A. DFA  
    B. NFA  
    C. Linear bounded automaton (LBA)  
    D. Turing machine without tape  

21. In a `for` loop `for (i=0; i<n; ++i)`, how many times is the condition `i<n` evaluated (assuming no `break`)?  
    A. `n`  
    B. `n+1`  
    C. `n-1`  
    D. Exactly 2  

22. Which OOP concept is most directly used to hide internal representation while exposing necessary operations?  
    A. Encapsulation  
    B. Inheritance  
    C. Polymorphism  
    D. Multiple inheritance  

23. The space complexity of storing an adjacency matrix for a graph with `n` vertices is:  
    A. `O(n)`  
    B. `O(n log n)`  
    C. `O(n^2)`  
    D. `O(2^n)`  

24. In SQL, `SELECT COUNT(*) FROM T WHERE condition;` returns:  
    A. Number of distinct values in table T  
    B. Number of rows in T  
    C. Number of rows in T satisfying `condition`  
    D. Number of columns in T  

25. In virtual memory, which page replacement algorithm is stack-based (i.e., does not exhibit Belady’s anomaly)?  
    A. FIFO  
    B. LRU  
    C. Random  
    D. Clock  

---

### Questions 26–50

26. A simple undirected graph with `n` vertices and no edges is:  
    A. Complete  
    B. Null graph  
    C. Tree  
    D. Bipartite but not connected  

27. For permutations `P(n,r)`, the value equals:  
    A. `n! / (n-r)!`  
    B. `n! / r!`  
    C. `r! / n!`  
    D. `n^r`  

28. In AI, Uniform Cost Search is equivalent to A* when:  
    A. `h(n) = 0` for all nodes  
    B. `h(n) = 1` for all nodes  
    C. `h(n)` is negative  
    D. `h(n)` is overestimating  

29. The pumping lemma for regular languages is typically applied by:  
    A. Exhibiting a DFA directly  
    B. Assuming language is regular and deriving a contradiction  
    C. Converting regex to NFA  
    D. Reducing from a known non-regular language directly  

30. Which software process model explicitly emphasizes risk analysis in each cycle?  
    A. Waterfall  
    B. Spiral  
    C. Agile Scrum only  
    D. V-model  

31. Which protocol is used to map IP addresses to MAC addresses on a LAN?  
    A. DNS  
    B. ARP  
    C. DHCP  
    D. ICMP  

32. In C-like languages, which of the following is safest regarding `sizeof(int)`?  
    A. It is always 2 bytes  
    B. It is always 4 bytes  
    C. It is implementation dependent  
    D. It is always equal to `sizeof(long)`  

33. Overloading decides which function to call based on:  
    A. Return type only  
    B. Parameter types and counts at compile time  
    C. Runtime object type  
    D. Access specifier  

34. The time complexity of BFS on a graph with V vertices and E edges using adjacency lists is:  
    A. `O(V)`  
    B. `O(E)`  
    C. `O(V+E)`  
    D. `O(VE)`  

35. An SQL `LEFT OUTER JOIN` between A and B on A.id = B.id returns:  
    A. Only rows with matching ids  
    B. All rows from A and matching from B, with NULLs for non-matches  
    C. All rows from B and matching from A  
    D. Only rows from B  

36. Preemptive SJF (Shortest Remaining Time First) can be considered:  
    A. Non-preemptive FCFS variant  
    B. Preemptive version of SJF  
    C. Equivalent to RR  
    D. Equivalent to FIFO page replacement  

37. A relation that is reflexive, antisymmetric, transitive, and also for any `a,b`, either `aRb` or `bRa` (or both) is:  
    A. Partial order  
    B. Total order  
    C. Equivalence relation  
    D. Symmetric relation  

38. In search, a heuristic `h` is consistent if for every edge `(n, n')` with cost `c`:  
    A. `h(n) <= h(n')`  
    B. `h(n) <= h(n') + c`  
    C. `h(n) >= h(n')`  
    D. `h(n) = 0`  

39. The language `{ a^n b^m | n,m >= 0 }` is:  
    A. Not regular  
    B. Regular  
    C. Not context-free  
    D. Finite  

40. Integration testing focuses on:  
    A. Individual functions in isolation  
    B. Interactions between modules/subsystems  
    C. Overall user acceptance  
    D. Performance under high load only  

41. Which protocol operates at the transport layer and uses port numbers?  
    A. IP  
    B. TCP  
    C. ARP  
    D. ICMP  

42. Which operator pair in C/C++ guarantees short-circuit evaluation?  
    A. `&` and `|`  
    B. `&&` and `||`  
    C. `+` and `-`  
    D. `*` and `/`  

43. In a max-heap of size `n`, the index range of all possible leaves (array implementation, 1-based indexing) is:  
    A. 1 to `n`  
    B. `2` to `n`  
    C. `n/2 + 1` to `n` (floor)  
    D. 0 to `n-1`  

44. A relation is in 2NF if it is in 1NF and:  
    A. Has no transitive dependencies  
    B. Has no partial dependencies on any candidate key  
    C. Has no foreign keys  
    D. Has all attributes functionally dependent on primary key only  

45. The main purpose of a ready queue in OS scheduling is to:  
    A. Hold processes waiting for I/O  
    B. Hold processes that are ready to run on CPU  
    C. Hold processes swapped out to disk  
    D. Store terminated processes  

46. In discrete math, `C(n,r)` counts:  
    A. Ordered arrangements (permutations)  
    B. Unordered selections (combinations)  
    C. Paths in a graph  
    D. Subgraphs  

47. A language recognized by some Turing machine that always halts on every input is:  
    A. Recursively enumerable but not recursive  
    B. Recursive (decidable)  
    C. Context-free  
    D. Regular only  

48. White-box testing is also known as:  
    A. Functional testing  
    B. Structural testing  
    C. Beta testing  
    D. System testing  

49. Which protocol is commonly used to retrieve email in a simple, download-and-delete model?  
    A. SMTP  
    B. POP3  
    C. IMAP  
    D. HTTP  

50. In the TCP/IP model, which layer roughly corresponds to the OSI network layer?  
    A. Application  
    B. Transport  
    C. Internet  
    D. Link  

---

### Questions 51–75

51. The expression `a && b || c` is parsed (in C-like precedence) as:  
    A. `(a && b) || c`  
    B. `a && (b || c)`  
    C. `(a || c) && b`  
    D. `a && b && c`  

52. In OOP, composition is preferred over inheritance when:  
    A. You need an is-a relationship  
    B. You want to reuse behavior flexibly without strong hierarchy coupling  
    C. You want to expose all base internals  
    D. You must share implementation of protected members  

53. For a graph with `V` vertices and `E` edges, storing as an adjacency list is more space-efficient than an adjacency matrix when:  
    A. Graph is dense (`E ≈ V^2`)  
    B. Graph is sparse (`E << V^2`)  
    C. Graph is complete  
    D. Graph is null  

54. In SQL, `GROUP BY` is used to:  
    A. Filter rows  
    B. Order rows  
    C. Partition rows into groups for aggregation  
    D. Remove duplicates  

55. In paging, external fragmentation is:  
    A. Typical and large  
    B. Eliminated, but internal fragmentation may remain  
    C. Worse than paging + segmentation  
    D. Required by OS design  

56. The size of the power set of a set of size `n` is:  
    A. `n`  
    B. `2n`  
    C. `2^n`  
    D. `n!`  

57. In search, a heuristic that is admissible but not consistent:  
    A. May still guarantee optimality with graph search but needs reopenings  
    B. Cannot be used in A*  
    C. Always overestimates  
    D. Is equivalent to Uniform Cost Search  

58. The language `{ a^i b^j | i,j >= 0 }` where `i=j` is:  
    A. Regular  
    B. CFL but not regular  
    C. Not CFL  
    D. Finite  

59. Corrective maintenance is primarily done to:  
    A. Correct faults/bugs discovered after deployment  
    B. Improve performance  
    C. Adapt to new platforms  
    D. Prevent future faults only  

60. Which protocol is typically used for remote terminal access (classic example)?  
    A. Telnet  
    B. DNS  
    C. ARP  
    D. ICMP  

61. Which C construct can cause “fall-through” behavior if `break` is omitted?  
    A. `if-else`  
    B. `switch`  
    C. `for`  
    D. `while`  

62. An abstract data type (ADT) is best defined as:  
    A. A concrete implementation of a data structure  
    B. A mathematical model with operations specified but not implementations  
    C. Any pointer type  
    D. A C struct with only public fields  

63. A graph is bipartite if and only if it:  
    A. Contains no edges  
    B. Contains no cycles  
    C. Contains no odd-length cycles  
    D. Contains no even-length cycles  

64. A relation in 3NF must not have:  
    A. Any dependencies  
    B. Partial dependencies  
    C. Transitive dependencies where non-key depends on non-key  
    D. Candidate keys  

65. The simplest form of deadlock prevention that breaks “hold and wait” does so by:  
    A. Allowing preemption of all resources  
    B. Forcing processes to request all resources at once  
    C. Circularly ordering resources  
    D. Increasing frame count  

66. In logic, `P → Q` is logically equivalent to:  
    A. `¬P ∨ Q`  
    B. `P ∧ Q`  
    C. `¬(P ∨ Q)`  
    D. `P ∧ ¬Q`  

67. A PDA with one stack recognizes exactly:  
    A. Regular languages  
    B. Context-free languages  
    C. Context-sensitive languages  
    D. Recursively enumerable languages  

68. Unit testing typically focuses on:  
    A. Whole system  
    B. Individual functions/classes in isolation  
    C. Integration of subsystems  
    D. Performance under stress  

69. DHCP is used to:  
    A. Map IP to MAC  
    B. Assign IP configuration dynamically  
    C. Resolve domain names  
    D. Transfer mail  

70. Which C/C++ issue can lead to undefined behavior?  
    A. Reading from initialized variable  
    B. Out-of-bounds array access  
    C. Using `sizeof` on a type  
    D. Using `==` with integers  

71. Which data structure is typically used for implementing a BFS frontier?  
    A. Stack  
    B. Queue  
    C. Heap  
    D. Hash table  

72. In SQL, which operation is used to combine rows from two tables that share some common attributes, keeping all rows from both tables and filling missing with NULL?  
    A. INNER JOIN  
    B. LEFT JOIN  
    C. FULL OUTER JOIN  
    D. CROSS JOIN  

73. Context switching overhead depends most directly on:  
    A. Process priority only  
    B. Size of PCB and frequency of switches  
    C. Disk speed  
    D. Database schema  

74. A deterministic finite automaton can recognize:  
    A. All and only regular languages  
    B. All context-free languages  
    C. All recursively enumerable languages  
    D. Only finite languages  

75. Load testing in software engineering aims to:  
    A. Validate logic correctness  
    B. Assess system behavior under expected or heavy load  
    C. Verify UI usability  
    D. Replace unit testing  

---

### Questions 76–100

76. In a set of 4 elements, the number of 2-element combinations is:  
    A. 4  
    B. 6  
    C. 8  
    D. 12  

77. Depth-first search on an infinite tree without cycle checking:  
    A. Is always complete  
    B. May fail to find a solution even if it exists  
    C. Is always optimal  
    D. Is equivalent to BFS  

78. In theory of computation, recursively enumerable languages are those for which:  
    A. Membership can be decided in finite time for all inputs  
    B. There exists a Turing machine that halts on all inputs not in the language  
    C. There exists a Turing machine that accepts strings in the language and may not halt otherwise  
    D. There exists a DFA that accepts them  

79. Low coupling between modules means:  
    A. Modules heavily depend on each other  
    B. Modules have minimal interdependencies  
    C. Modules share global variables widely  
    D. Modules must be modified together  

80. In TCP, flow control primarily prevents:  
    A. Network congestion  
    B. Sender from overwhelming receiver’s buffer  
    C. IP fragmentation  
    D. DNS lookup failures  

81. In C, expression `5 / 2 * 2` evaluates to:  
    A. 5  
    B. 4  
    C. 6  
    D. 2  

82. A complete binary tree with `n` nodes has height on the order of:  
    A. `O(1)`  
    B. `O(log n)`  
    C. `O(n)`  
    D. `O(n log n)`  

83. 2NF specifically removes:  
    A. Partial dependencies on any candidate key  
    B. All transitive dependencies  
    C. All functional dependencies  
    D. All foreign keys  

84. A context switch occurs when:  
    A. CPU switches from kernel mode to user mode without changing process  
    B. CPU switches from running one process/thread to another  
    C. RAM is swapped to disk  
    D. DNS resolves a new address  

85. Mathematical induction typically proves statements for:  
    A. Real numbers  
    B. Natural numbers or well-ordered sets  
    C. Arbitrary graphs  
    D. All languages  

86. The language `{ w w^R | w in {0,1}* }` (even-length palindromes) is:  
    A. Regular  
    B. CFL but not regular  
    C. Not CFL  
    D. Finite  

87. System testing is primarily focused on:  
    A. Individual units  
    B. Integrated system against functional and non-functional requirements  
    C. Interface between two modules only  
    D. Internal implementation correctness  

88. For streaming applications (voice, video), UDP is often preferred because:  
    A. It guarantees in-order delivery  
    B. It has lower overhead and can tolerate occasional loss  
    C. It provides built-in congestion control  
    D. It encrypts payload  

89. The `volatile` keyword in C typically indicates:  
    A. Variable stored on disk  
    B. Variable may change outside program control (e.g., hardware)  
    C. Variable cannot be modified  
    D. Variable is thread-local automatically  

90. In Kruskal’s algorithm, the next edge chosen is:  
    A. Any edge incident to current tree  
    B. The smallest-weight edge that does not form a cycle  
    C. The largest-weight edge  
    D. Any edge in BFS order  

91. Regular languages are closed under:  
    A. Union  
    B. Intersection  
    C. Complement  
    D. All of the above  

92. Acceptance testing is usually done to:  
    A. Check adherence to coding standards  
    B. Validate system against business/user requirements  
    C. Test individual modules  
    D. Stress test database  

93. The main role of a router is to:  
    A. Connect multiple collision domains at layer 2  
    B. Forward packets between networks based on IP addresses  
    C. Amplify electrical signals only  
    D. Resolve hostnames  

94. Starvation in scheduling occurs when:  
    A. Processes are deadlocked  
    B. A process waits indefinitely due to resource allocation policy  
    C. CPU utilization is too high  
    D. Queue is empty  

95. In graph terms, a tree is:  
    A. Connected and acyclic  
    B. Acyclic, not necessarily connected  
    C. Connected, may contain cycles  
    D. Always complete  

96. Turing machines are strictly more powerful than finite automata because:  
    A. They have more states  
    B. They have an unbounded tape and can simulate memory  
    C. They run faster  
    D. They always halt  

97. A non-functional requirement example is:  
    A. User can reset password  
    B. System must respond within 1 second for 95% of requests  
    C. System must send weekly reports  
    D. System must compute GPA  

98. DNS is primarily used to:  
    A. Map IP to MAC  
    B. Map hostnames to IP addresses  
    C. Assign IP addresses dynamically  
    D. Transfer email  

99. Which of the following is a regular language?  
    A. `{ a^n b^n | n >= 0 }`  
    B. `{ a^n b^n c^n | n >= 0 }`  
    C. `{ w in {0,1}* | w contains exactly two 1s }`  
    D. `{ w w | w in {0,1}* }`  

100. In a no-negative-marking MCQ exam, the best strategy after eliminating one or two options is to:  
     A. Leave the question unanswered  
     B. Guess among remaining options  
     C. Skip all tough questions  
     D. Answer only first half of paper  

---

## Answer Key – Mock Test 2

| Q | Ans | Q | Ans | Q | Ans | Q | Ans |
|---|---|---|---|---|---|---|---|
| 1 | C | 26 | B | 51 | A | 76 | B |
| 2 | B | 27 | A | 52 | B | 77 | B |
| 3 | A | 28 | A | 53 | B | 78 | C |
| 4 | A | 29 | B | 54 | C | 79 | B |
| 5 | B | 30 | B | 55 | B | 80 | B |
| 6 | B | 31 | B | 56 | C | 81 | B |
| 7 | B | 32 | C | 57 | A | 82 | B |
| 8 | B | 33 | B | 58 | B | 83 | A |
| 9 | D | 34 | C | 59 | A | 84 | B |
|10 | C | 35 | B | 60 | A | 85 | B |
|11 | C | 36 | B | 61 | B | 86 | B |
|12 | D | 37 | B | 62 | B | 87 | B |
|13 | B | 38 | B | 63 | C | 88 | B |
|14 | B | 39 | B | 64 | C | 89 | B |
|15 | C | 40 | B | 65 | B | 90 | B |
|16 | D | 41 | D | 66 | A | 91 | D |
|17 | C | 42 | B | 67 | B | 92 | B |
|18 | B | 43 | C | 68 | B | 93 | B |
|19 | C | 44 | B | 69 | B | 94 | B |
|20 | C | 45 | B | 70 | B | 95 | A |
|21 | B | 46 | B | 71 | B | 96 | B |
|22 | A | 47 | B | 72 | C | 97 | B |
|23 | C | 48 | B | 73 | B | 98 | B |
|24 | C | 49 | B | 74 | A | 99 | C |
|25 | B | 50 | C | 75 | B |100 | B |

### Quick Notes on Common Traps

- Integer/side-effect traps: Q12 (undefined behavior), Q21, Q31, Q51, Q70, Q81 rely on precedence, off-by-one, and UB understanding.  
- Language class traps: Q8, Q20, Q28, Q38, Q39, Q58, Q67, Q71, Q74, Q78, Q86, Q91, Q99 test regular/CFL/context-sensitive/RE distinctions.  
- OS and DB traps: Q25, Q35, Q44, Q55, Q83 focus on page replacement, thrashing, MST, and normalization nuances.  
- Networks traps: Q11, Q31, Q41, Q49, Q50, Q60, Q69, Q80, Q93, Q98 test protocol–layer mapping and TCP/UDP roles.  
- Strategy trap: Q100 reinforces that with no negative marking, elimination + guessing dominates leaving blanks.
