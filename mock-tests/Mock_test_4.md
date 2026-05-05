# Full-Length Mock Test 4 (100 MCQs)

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

- 100 single-best-answer MCQs
- No negative marking assumed
- Solve under time pressure; mark doubtful ones for second pass

---

## Questions 1–25

1. In C-like languages, which statement about `int` is safest?  
   A. It is always 16 bits  
   B. It is always 32 bits  
   C. Its size is implementation-dependent  
   D. It is always the same size as `long long`  

2. Which OOP principle focuses on exposing only relevant operations while hiding internal details?  
   A. Encapsulation  
   B. Inheritance  
   C. Polymorphism  
   D. Coupling  

3. The worst-case time complexity of binary search on a sorted array is:  
   A. `O(1)`  
   B. `O(log n)`  
   C. `O(n)`  
   D. `O(n log n)`  

4. In the relational model, a candidate key is:  
   A. Any attribute set that uniquely identifies tuples  
   B. A minimal super key  
   C. Always composite  
   D. Only an attribute in another relation  

5. In OS scheduling, turnaround time is:  
   A. Time spent in ready queue  
   B. Time from process arrival to completion  
   C. Time from arrival to first response  
   D. Total CPU time used  

6. A relation R on A is transitive if:  
   A. `aRa` for all a  
   B. `aRb` implies `bRa`  
   C. `aRb` and `bRc` imply `aRc`  
   D. `aRb` and `bRa` imply `a=b`  

7. Uniform Cost Search reduces to BFS when:  
   A. Heuristic is admissible  
   B. All step costs are equal  
   C. Heuristic is zero and costs vary  
   D. Graph is acyclic  

8. Which language is regular?  
   A. `{ a^n b^n | n ≥ 0 }`  
   B. `{ w ∈ {0,1}* | w has exactly two 0s }`  
   C. `{ a^n b^n c^n | n ≥ 0 }`  
   D. `{ ww | w ∈ {0,1}* }`  

9. Which machine model corresponds to context-free languages?  
   A. DFA  
   B. NFA  
   C. PDA  
   D. TM with two tapes  

10. Which process model is most appropriate when requirements are initially unclear and likely to evolve?  
    A. Waterfall  
    B. Agile / iterative  
    C. Strict V-model  
    D. Big-bang  

11. Which protocol operates at the application layer and is stateless by default?  
    A. TCP  
    B. HTTP  
    C. IP  
    D. ARP  

12. In C-like languages, `y = ++x;` does:  
    A. Assign old x to y, then increment x  
    B. Increment x, then assign new x to y  
    C. Assign 1 to y always  
    D. Is illegal syntax  

13. In OOP, function overloading is resolved:  
    A. At compile time based on parameter types  
    B. At run time based on object type  
    C. Only with virtual functions  
    D. Only with templates  

14. The average time complexity of insertion sort on random data is:  
    A. `O(n)`  
    B. `O(n log n)`  
    C. `O(n^2)`  
    D. `O(1)`  

15. A relation is in 3NF if it is in 2NF and additionally has:  
    A. No functional dependencies  
    B. No transitive dependencies from key to non-key via non-key  
    C. No partial dependencies  
    D. No foreign keys  

16. Which scheduling algorithm can cause starvation of long jobs if not carefully managed?  
    A. FCFS  
    B. SJF (non-preemptive)  
    C. RR  
    D. FCFS with large quantum  

17. A function `f: A → B` is injective if:  
    A. Every element of B has at least one preimage  
    B. Different elements of A map to different elements of B  
    C. A and B have the same size  
    D. It is surjective  

18. In AI, which search is “uninformed” (no heuristic)?  
    A. A*  
    B. Greedy Best-First  
    C. Uniform Cost Search  
    D. Hill Climbing  

19. Pumping lemma for regular languages is typically used to:  
    A. Construct DFAs  
    B. Show some languages are not regular  
    C. Show closure under union  
    D. Minimize NFAs  

20. Which network device forwards frames based on MAC addresses and reduces collision domains?  
    A. Hub  
    B. Switch  
    C. Repeater  
    D. Bridge (classic)  

21. In C, reading from an uninitialized local `int x; printf("%d", x);` is:  
    A. Well-defined and prints 0  
    B. Well-defined and prints 1  
    C. Undefined behavior / indeterminate output  
    D. Compile-time error  

22. Composition in OOP best models which relationship?  
    A. Car is-a Vehicle  
    B. Car has-an Engine  
    C. Student is-a Person  
    D. Square is-a Rectangle  

23. For an adjacency-list representation with `V` vertices and `E` edges, BFS time complexity is:  
    A. `O(V)`  
    B. `O(E)`  
    C. `O(V+E)`  
    D. `O(VE)`  

24. In SQL, to remove duplicate rows in the result of a query, use:  
    A. GROUP BY  
    B. HAVING  
    C. DISTINCT  
    D. ORDER BY  

25. A page replacement algorithm that always replaces the page that will not be used for the longest time in future is:  
    A. FIFO  
    B. LRU  
    C. Optimal  
    D. Clock  

---

## Questions 26–50

26. A simple graph with no cycles is:  
    A. Tree if connected  
    B. Complete graph  
    C. Always bipartite and connected  
    D. Null graph  

27. Number of combinations of `n` elements taken `r` at a time is:  
    A. `n! / (n-r)!`  
    B. `n! / (r!(n-r)!)`  
    C. `n^r`  
    D. `r^n`  

28. In AI, Greedy Best-First Search chooses the node with:  
    A. Minimal `g(n)`  
    B. Minimal `h(n)`  
    C. Minimal `g(n) + h(n)`  
    D. Maximal `h(n)`  

29. The language `{ w w^R | w ∈ {0,1}* }` (even-length palindromes) is:  
    A. Regular  
    B. Context-free but not regular  
    C. Not context-free  
    D. Finite  

30. In software process, a prototype is mainly built to:  
    A. Replace final system  
    B. Explore and clarify requirements  
    C. Minimize testing effort  
    D. Avoid documentation  

31. DNS primarily maps:  
    A. IP to MAC  
    B. Hostname to IP address  
    C. Port to IP  
    D. IP to hostname only  

32. In C, which expression is true about operator precedence?  
    A. `*` and `/` have lower precedence than `+`  
    B. `&&` has higher precedence than `||`  
    C. Assignment `=` has higher precedence than `==`  
    D. `||` has higher precedence than `&&`  

33. In OOP, a virtual destructor in base class is important because:  
    A. It prevents object creation  
    B. It ensures correct destructor of derived class is called via base pointer  
    C. It prevents slicing  
    D. It disables polymorphism  

34. In a heap-based priority queue, removing the minimum in a min-heap costs:  
    A. `O(1)`  
    B. `O(log n)`  
    C. `O(n)`  
    D. `O(n log n)`  

35. In SQL, which command is used to change the schema of an existing table (e.g., add column)?  
    A. ALTER TABLE  
    B. UPDATE TABLE  
    C. MODIFY SCHEMA  
    D. APPEND COLUMN  

36. External fragmentation occurs when:  
    A. Free memory is split into many small non-contiguous blocks  
    B. Allocated blocks are partially empty  
    C. Pages are all fixed size  
    D. Processes are swapped out  

37. Sum of degrees of all vertices in an undirected graph equals:  
    A. Number of vertices  
    B. Number of edges  
    C. Twice the number of edges  
    D. `V + E`  

38. A heuristic h is consistent if for every edge n→n′ of cost c:  
    A. `h(n) <= h(n′)`  
    B. `h(n) <= h(n′) + c`  
    C. `h(n) >= h(n′) + c`  
    D. `h(n) = 0`  

39. The language `{ a^n b^m | n,m ≥ 0 }` is:  
    A. Not regular  
    B. Regular  
    C. Not context-free  
    D. Finite  

40. In software testing, integration testing focuses on:  
    A. Individual units  
    B. Combined modules and their interactions  
    C. System against user requirements  
    D. Non-functional attributes only  

41. Transport-layer protocol used for unreliable datagram transmission is:  
    A. TCP  
    B. UDP  
    C. HTTP  
    D. ICMP  

42. In C, logical AND `&&` differs from bitwise AND `&` because:  
    A. `&&` evaluates operands as integers, `&` as booleans  
    B. `&&` short-circuits, `&` does not  
    C. `&` short-circuits, `&&` does not  
    D. Both short-circuit  

43. Maximum number of nodes in a binary tree of height h (root height 0) is:  
    A. `2^h`  
    B. `2^(h+1) - 1`  
    C. `h^2`  
    D. `h!`  

44. BCNF strengthens 3NF by requiring:  
    A. Every determinant is a candidate key  
    B. Every dependent is a key  
    C. No foreign keys  
    D. No composite keys  

45. Deadlock prevention via “request all resources at once” breaks which condition?  
    A. Mutual exclusion  
    B. Hold and wait  
    C. No preemption  
    D. Circular wait  

46. A contradiction in propositional logic is a statement that is:  
    A. Always true  
    B. Always false  
    C. Sometimes true, sometimes false  
    D. Independent of valuations  

47. A DPDA (deterministic PDA) recognizes:  
    A. All CFLs  
    B. Exactly the regular languages  
    C. A proper subset of CFLs  
    D. All decidable languages  

48. System testing is primarily to:  
    A. Test isolated modules  
    B. Validate the integrated system against specified requirements  
    C. Load-test database  
    D. Detect memory leaks only  

49. ARP is used for:  
    A. Mapping hostnames to IP  
    B. Assigning IP addresses  
    C. Mapping IP addresses to MAC addresses on a LAN  
    D. Transferring email  

50. Which C library function is especially dangerous if buffer size is not checked?  
    A. `strlen`  
    B. `strcpy`  
    C. `strcmp`  
    D. `strchr`  

---

## Questions 51–75

51. BFS typically uses which data structure for its frontier?  
    A. Stack  
    B. Queue  
    C. Priority queue  
    D. Linked list only  

52. An `INNER JOIN` between A and B on A.id = B.id returns:  
    A. All rows from A  
    B. All rows from B  
    C. Only rows where A.id = B.id in both tables  
    D. All rows from A and B regardless of match  

53. Starvation in OS scheduling occurs when:  
    A. Processes are in circular wait  
    B. A process waits indefinitely because resources always go to others  
    C. CPU utilization is low  
    D. I/O devices are unused  

54. DFA and NFA are:  
    A. NFAs more powerful than DFAs  
    B. DFAs more powerful than NFAs  
    C. Equivalent in expressive power  
    D. Incomparable  

55. Load testing aims to:  
    A. Verify correctness of individual functions  
    B. Determine system behavior under normal and peak expected load  
    C. Replace unit tests  
    D. Verify code style  

56. Number of subsets of a set with 8 elements is:  
    A. 16  
    B. 64  
    C. 128  
    D. 256  

57. DFS on an infinite graph without cycle detection is:  
    A. Complete  
    B. May fail to find an existing solution  
    C. Always optimal  
    D. Equivalent to BFS  

58. Recursively enumerable languages are those for which:  
    A. Membership can be decided for every input in finite time  
    B. Some Turing machine accepts all strings in the language (and may loop on others)  
    C. There is a DFA recognizing them  
    D. They are all context-free  

59. High cohesion in a module implies:  
    A. Module responsibilities are closely related  
    B. Module responsibilities are unrelated  
    C. Module uses many global variables  
    D. Module strongly depends on many others  

60. TCP flow control mainly prevents:  
    A. Network congestion  
    B. Sender from overwhelming receiver’s buffer  
    C. DNS lookup failures  
    D. ARP cache overflow  

61. In C, `9 / 4 * 4` evaluates to:  
    A. 9  
    B. 8  
    C. 4  
    D. 2  

62. Height of a complete binary tree with n nodes is approximately:  
    A. `O(1)`  
    B. `O(log n)`  
    C. `O(n)`  
    D. `O(n log n)`  

63. 2NF removes which type of dependency?  
    A. Any dependency  
    B. Partial dependency of non-key on part of composite key  
    C. Transitive dependency of non-key on non-key  
    D. Foreign key dependency  

64. Context switching involves saving and restoring:  
    A. Global variables only  
    B. PCB (registers, PC, state, etc.)  
    C. Disk contents  
    D. Entire address space content every time  

65. Mathematical induction on natural numbers uses:  
    A. Base case + inductive step  
    B. Base case + contradiction  
    C. Only examples  
    D. Only counterexamples  

66. Language `{ a^n b^n c^n | n ≥ 0 }` is:  
    A. Regular  
    B. Context-free  
    C. Not context-free  
    D. Finite  

67. Black-box testing focuses on:  
    A. Internal code structure  
    B. Input-output behavior vs requirements  
    C. Memory layout  
    D. CPU pipeline  

68. For real-time video streaming, UDP is often preferred because:  
    A. It guarantees ordered delivery  
    B. It has lower overhead and slight loss is acceptable  
    C. It does congestion control by default  
    D. It encrypts traffic  

69. In C, the `volatile` keyword indicates:  
    A. Variable must be constant  
    B. Variable may change asynchronously outside program control  
    C. Variable is local only  
    D. Variable is on disk  

70. Dijkstra’s algorithm fails if:  
    A. Graph is directed  
    B. Graph has negative edge weights  
    C. Graph is weighted  
    D. Graph is connected  

71. Regular languages are closed under:  
    A. Union and intersection  
    B. Complement  
    C. Concatenation and Kleene star  
    D. All of the above  

72. Acceptance testing is primarily performed by:  
    A. Developers only  
    B. Clients/end users or representatives  
    C. Compiler  
    D. OS kernel  

73. A router works mainly at OSI layer:  
    A. 2  
    B. 3  
    C. 4  
    D. 7  

74. Aging in scheduling is used to:  
    A. Detect deadlock  
    B. Gradually increase priority of waiting processes to reduce starvation  
    C. Decrease CPU utilization  
    D. Reduce context switches  

75. A tree (in graph theory) is:  
    A. Connected, acyclic, and has n-1 edges for n vertices  
    B. Disconnected and acyclic  
    C. Connected with at least one cycle  
    D. Always complete  

---

## Questions 76–100

76. `C(6,3)` equals:  
    A. 6  
    B. 18  
    C. 20  
    D. 60  

77. BFS on an infinite tree with branching factor > 1:  
    A. Is complete if a solution exists at finite depth  
    B. May miss shallow solutions  
    C. Is always optimal even with varying costs  
    D. Is identical to DFS  

78. In computation theory, a language is decidable if:  
    A. Some Turing machine halts and answers yes/no on every input  
    B. Some Turing machine accepts it but may loop on non-members  
    C. Some DFA accepts it  
    D. Some PDA accepts it  

79. Low coupling between modules means:  
    A. Modules highly depend on each other  
    B. Modules have minimal interdependencies  
    C. Modules must be modified together  
    D. Modules share global state extensively  

80. TCP congestion control primarily aims to:  
    A. Avoid receiver buffer overflow  
    B. Prevent network overload and collapse  
    C. Guarantee zero loss  
    D. Compress data  

81. In C, integer expression `7 / 3 * 3` evaluates to:  
    A. 7  
    B. 6  
    C. 9  
    D. 3  

82. A complete binary tree with `n` nodes has:  
    A. All levels fully filled  
    B. All levels except possibly last completely filled, last filled from left  
    C. Only one child per node  
    D. Exactly one leaf  

83. 3NF removes:  
    A. All FDs  
    B. Transitive dependencies where non-key depends on non-key via key  
    C. All candidate keys  
    D. All partial dependencies  

84. Context switch overhead is influenced primarily by:  
    A. Size of process state and frequency of switches  
    B. Disk size  
    C. Network topology  
    D. Number of SQL queries  

85. Induction proof: if P(1) holds and P(k)→P(k+1) for all k, you can conclude:  
    A. P(n) for all natural n ≥ 1  
    B. P(n) for some n  
    C. P(n) for even n only  
    D. Nothing guaranteed  

86. DFA can recognize:  
    A. All and only regular languages  
    B. All CFLs  
    C. All RE languages  
    D. All decidable languages  

87. System testing validates:  
    A. Unit-level algorithms only  
    B. Entire integrated system against functional and non-functional requirements  
    C. Only performance metrics  
    D. Only UI  

88. UDP is best choice when:  
    A. Reliability is critical  
    B. Lower latency and tolerance for loss are acceptable  
    C. Transactions require exactly-once delivery  
    D. File transfer requires integrity  

89. `register` keyword in C historically hints that:  
    A. Variable should be stored on stack  
    B. Compiler may keep variable in CPU register for faster access  
    C. Variable is constant  
    D. Variable is global  

90. Kruskal’s algorithm builds MST by:  
    A. Growing one tree from an arbitrary root  
    B. Adding edges in increasing weight order, skipping those that form cycles  
    C. Using Dijkstra’s distances  
    D. Using topological order  

91. The set of regular languages is closed under:  
    A. Union  
    B. Intersection  
    C. Complement  
    D. All of the above  

92. In acceptance testing, success means:  
    A. Code compiles  
    B. Users/clients accept system as meeting requirements  
    C. 100% statement coverage  
    D. Zero bugs  

93. A router’s main function is to:  
    A. Forward frames within a LAN  
    B. Forward packets between networks using IP addresses  
    C. Resolve MAC addresses  
    D. Perform DNS lookups  

94. Starvation can occur in priority scheduling when:  
    A. Priorities are all equal  
    B. New high-priority jobs keep arriving and low-priority never gets CPU  
    C. Time quantum is large  
    D. FCFS is used  

95. A tree with n vertices has:  
    A. n edges  
    B. n-1 edges  
    C. n+1 edges  
    D. 2n edges  

96. Turing machines are more powerful than finite automata because:  
    A. They can use an unbounded tape for memory  
    B. They always run faster  
    C. They are deterministic  
    D. They use fewer states  

97. A non-functional requirement example is:  
    A. System must support online payment  
    B. System must authenticate user with OTP  
    C. System must respond within 2 seconds for 95% of requests  
    D. System must generate monthly sales report  

98. DHCP primarily:  
    A. Assigns IP configuration dynamically  
    B. Resolves hostnames  
    C. Maps IP to MAC  
    D. Transfers email  

99. Which of the following is regular?  
    A. `{ a^n b^n | n ≥ 0 }`  
    B. `{ a^n b^n c^n | n ≥ 0 }`  
    C. `{ w ∈ {0,1}* | w has at most 2 ones }`  
    D. `{ w w | w ∈ {0,1}* }`  

100. With no negative marking, after eliminating one or more options, the rational strategy is to:  
     A. Leave the question blank  
     B. Guess among remaining options  
     C. Attempt only ones you are fully sure about  
     D. Answer only first half of paper  

---

## Answer Key – Mock Test 4

| Q | Ans | Q | Ans | Q | Ans | Q | Ans |
|---|---|---|---|---|---|---|---|
| 1 | C | 26 | A | 51 | B | 76 | C |
| 2 | A | 27 | B | 52 | C | 77 | A |
| 3 | B | 28 | B | 53 | B | 78 | A |
| 4 | B | 29 | B | 54 | C | 79 | B |
| 5 | B | 30 | B | 55 | B | 80 | B |
| 6 | C | 31 | B | 56 | D | 81 | B |
| 7 | B | 32 | B | 57 | B | 82 | B |
| 8 | B | 33 | B | 58 | B | 83 | B |
| 9 | C | 34 | B | 59 | A | 84 | A |
|10 | B | 35 | A | 60 | B | 85 | A |
|11 | B | 36 | A | 61 | B | 86 | C |
|12 | B | 37 | C | 62 | B | 87 | B |
|13 | A | 38 | B | 63 | B | 88 | B |
|14 | C | 39 | B | 64 | B | 89 | B |
|15 | B | 40 | B | 65 | A | 90 | B |
|16 | B | 41 | B | 66 | C | 91 | D |
|17 | B | 42 | B | 67 | B | 92 | B |
|18 | C | 43 | B | 68 | B | 93 | B |
|19 | B | 44 | A | 69 | B | 94 | B |
|20 | B | 45 | B | 70 | B | 95 | B |
|21 | C | 46 | B | 71 | D | 96 | A |
|22 | B | 47 | C | 72 | B | 97 | C |
|23 | C | 48 | B | 73 | B | 98 | A |
|24 | C | 49 | C | 74 | B | 99 | C |
|25 | C | 50 | B | 75 | B |100 | B |

### Notes

- Core FAST BS CS topics (PF, OOP, DSA, DB, OS, Discrete, Automata, AI, Networks, SE) are all represented, reflecting the university’s own core curriculum guidelines.[web:19][web:48]  
- MCQs emphasize conceptual understanding, pitfalls (undefined behavior, deadlock conditions, normalization), and classification (regular vs CFL vs non-CFL), matching typical instructor-level screening expectations.
