# Full-Length Mock Test 5 (100 MCQs)

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
- Use at least two passes: first for sure shots, second for elimination-based guesses

---

## Questions 1–25

1. In C/C++-style languages, what is the usual result of `17 / 4` using integer division?  
   A. 4.25  
   B. 5  
   C. 4  
   D. Undefined at compile time  

2. Which OOP concept ensures that internal state is accessed only through specified methods?  
   A. Inheritance  
   B. Encapsulation  
   C. Polymorphism  
   D. Aggregation  

3. In a sorted array of size `n`, the worst-case number of comparisons in binary search is about:  
   A. `log2 n`  
   B. `n`  
   C. `n/2`  
   D. `sqrt(n)`  

4. In the relational model, a foreign key is:  
   A. A minimal super key  
   B. An attribute set that references a key in another relation  
   C. Always a candidate key in the same relation  
   D. Never nullable  

5. In OS, which of the following is a measure of “how many processes complete per unit time”?  
   A. CPU utilization  
   B. Turnaround time  
   C. Response time  
   D. Throughput  

6. A relation R on set A is antisymmetric if:  
   A. `aRb` implies `bRa`  
   B. `aRb` and `bRa` imply `a=b`  
   C. `aRb` and `bRc` imply `aRc`  
   D. `aRa` for all a  

7. Uniform Cost Search is guaranteed optimal when:  
   A. All step costs are equal and positive  
   B. Some costs are negative  
   C. Costs are arbitrary and heuristic is used  
   D. Branching factor is infinite  

8. Which of the following is context-free but not regular?  
   A. `{ a^n | n ≥ 0 }`  
   B. `{ a^n b^n | n ≥ 0 }`  
   C. `{ a^n b^n c^n | n ≥ 0 }`  
   D. Finite set of strings over `{a,b}`  

9. A deterministic finite automaton (DFA) recognizes exactly:  
   A. Regular languages  
   B. Context-free languages  
   C. Context-sensitive languages  
   D. Recursively enumerable languages  

10. Which software process model is explicitly iterative and incremental with time-boxed sprints?  
    A. Waterfall  
    B. Agile (e.g., Scrum)  
    C. V-model  
    D. Big-bang  

11. Which protocol operates at the transport layer in the TCP/IP model and is connection-oriented?  
    A. HTTP  
    B. TCP  
    C. IP  
    D. UDP  

12. In C, what does `z = x-- + 5;` do?  
    A. Uses current value of x in expression, then decrements x  
    B. Decrements x, then uses new value in expression  
    C. Sets x to x+5 and z to 0  
    D. Is undefined by standard  

13. In OOP, dynamic dispatch is achieved primarily via:  
    A. Function overloading  
    B. Virtual functions / method overriding  
    C. Macros  
    D. Templates  

14. The average time complexity of quicksort on random input is:  
    A. `O(n)`  
    B. `O(n log n)`  
    C. `O(n^2)`  
    D. `O(log n)`  

15. A relation is in 2NF if it is in 1NF and:  
    A. Has no transitive dependencies  
    B. Has no partial dependencies on any candidate key  
    C. Has no foreign keys  
    D. Has only single-attribute keys  

16. SJF (non-preemptive) scheduling chooses the process with:  
    A. Highest priority value  
    B. Longest CPU burst  
    C. Shortest CPU burst among ready processes  
    D. Smallest arrival time only  

17. A bijection between sets A and B is:  
    A. Many-to-one mapping  
    B. One-to-many mapping  
    C. One-to-one and onto mapping  
    D. A function defined only on a subset of A  

18. In AI, which of the following is an uninformed search strategy?  
    A. Greedy Best-First  
    B. A*  
    C. DFS  
    D. Best-first with heuristic  

19. Pumping lemma for regular languages gives:  
    A. A method to construct a minimal DFA  
    B. A necessary property that all infinite regular languages satisfy  
    C. A sufficient property for regularity  
    D. A closure property under concatenation  

20. Which network device primarily forwards packets between networks based on IP addresses?  
    A. Hub  
    B. Switch  
    C. Router  
    D. Repeater  

21. In C, accessing `a[-1]` for an array `int a[10];` is:  
    A. Defined as reading a[9]  
    B. Defined as reading a[0]  
    C. Undefined behavior / out-of-bounds access  
    D. Compile-time syntax error  

22. Inheritance primarily encodes which relationship?  
    A. has-a  
    B. uses-a  
    C. is-a  
    D. part-of  

23. For adjacency matrix representation of a graph with V vertices, space complexity is:  
    A. `O(V)`  
    B. `O(V^2)`  
    C. `O(V+E)`  
    D. `O(E)`  

24. In SQL, which clause limits the number of rows returned (in many dialects)?  
    A. GROUP BY  
    B. HAVING  
    C. LIMIT (or TOP)  
    D. DISTINCT  

25. In virtual memory, thrashing occurs when:  
    A. Page faults are very frequent and CPU mostly swaps pages  
    B. There are no page faults  
    C. CPU is always idle  
    D. File system is fragmented  

---

## Questions 26–50

26. A tree (connected acyclic graph) with `n` vertices must have:  
    A. `n` edges  
    B. `n-1` edges  
    C. `n+1` edges  
    D. `2n` edges  

27. The number of permutations of length r from n distinct elements is:  
    A. `C(n,r)`  
    B. `P(n,r) = n! / (n-r)!`  
    C. `n^r`  
    D. `r^n`  

28. A* search with heuristic `h(n) = 0` for all n behaves like:  
    A. Greedy Best-First Search  
    B. Uniform Cost Search  
    C. DFS  
    D. Hill climbing  

29. The language `{ 0^i 1^j | i = j }` is:  
    A. Regular  
    B. Context-free but not regular  
    C. Not context-free  
    D. Finite  

30. In prototyping model, the main goal of the prototype is to:  
    A. Replace the final product  
    B. Clarify requirements and refine understanding  
    C. Fully optimize performance  
    D. Eliminate the need for testing  

31. Which protocol is typically used for secure web browsing?  
    A. HTTP  
    B. HTTPS  
    C. FTP  
    D. SMTP  

32. In C, which expression is parsed as `(a && b) || c` due to precedence?  
    A. `a && b || c`  
    B. `a || b && c`  
    C. `a && (b || c)`  
    D. `(a || b) && c`  

33. A pure virtual function in C++ indicates that:  
    A. Class is abstract and cannot be instantiated  
    B. Function cannot be overridden  
    C. Function has a default implementation  
    D. Class cannot be inherited  

34. For a binary min-heap, inserting a new key has worst-case complexity:  
    A. `O(1)`  
    B. `O(log n)`  
    C. `O(n)`  
    D. `O(n log n)`  

35. In SQL, which command permanently deletes a table and its definition?  
    A. DELETE TABLE T  
    B. DROP TABLE T  
    C. TRUNCATE TABLE T  
    D. REMOVE TABLE T  

36. Internal fragmentation arises in fixed-partition allocation mainly because:  
    A. Partitions are variable sized  
    B. Processes do not use the full space of their partitions  
    C. There are too many page faults  
    D. Virtual memory is not used  

37. In a simple undirected graph, sum of degrees of vertices equals:  
    A. E  
    B. V  
    C. 2E  
    D. V+E  

38. An admissible heuristic:  
    A. Never underestimates  
    B. Never overestimates true cost to goal  
    C. Always equals true cost exactly  
    D. Can be any function  

39. The language `{ a^n b^m | n,m ≥ 0 }` is:  
    A. Regular (a* b*)  
    B. Not regular  
    C. Not context-free  
    D. Finite  

40. Regression testing is mainly to:  
    A. Check performance under peak load  
    B. Ensure new changes haven’t broken existing features  
    C. Validate requirements with users  
    D. Assess security  

41. The OSI layer responsible for path determination and logical addressing is:  
    A. Data Link  
    B. Network  
    C. Transport  
    D. Session  

42. In C, bitwise OR operator is:  
    A. `|`  
    B. `||`  
    C. `&`  
    D. `&&`  

43. In a complete binary tree of height h (root height 0), maximum nodes are:  
    A. `2^h`  
    B. `2^(h+1) - 1`  
    C. `h^2`  
    D. `2h`  

44. In 3NF, for a dependency X → Y, a relation is allowed if:  
    A. X is a superkey, or Y is prime attribute  
    B. Y is superkey only  
    C. X and Y are disjoint  
    D. X is subset of Y  

45. One way to prevent deadlock is to:  
    A. Allow hold and wait  
    B. Enforce a total ordering on resource acquisition  
    C. Disable mutual exclusion  
    D. Increase number of resources indefinitely  

46. A tautology in propositional logic is:  
    A. Always true under every valuation  
    B. Always false  
    C. Sometimes true, sometimes false  
    D. Not evaluable  

47. A PDA (with stack) can recognize exactly:  
    A. Regular languages  
    B. Context-free languages  
    C. Context-sensitive languages  
    D. Recursive languages  

48. Unit testing focuses on:  
    A. Single function or class in isolation  
    B. Integration of modules  
    C. Whole system under realistic load  
    D. User acceptance  

49. Which protocol resolves IPv4 addresses to MAC addresses in a LAN?  
    A. DNS  
    B. ARP  
    C. DHCP  
    D. ICMP  

50. Which C function is most likely to cause buffer overflow if destination size is not checked?  
    A. `strlen`  
    B. `strcpy`  
    C. `strcmp`  
    D. `strncpy` (with correct size)  

---

## Questions 51–75

51. BFS typically uses which structure for the frontier?  
    A. Stack  
    B. Queue  
    C. Priority queue  
    D. Hash table  

52. A `LEFT OUTER JOIN` between A and B (A left, condition A.id=B.id) returns:  
    A. Only matches  
    B. All rows from A and matching from B, NULL if no match  
    C. All rows from B only  
    D. All rows from both tables regardless of match  

53. Starvation in OS scheduling means:  
    A. CPU utilization is zero  
    B. A process may never be scheduled despite being ready  
    C. Processes are in circular wait  
    D. System is thrashing  

54. Regular languages are recognized by:  
    A. DFA / NFA  
    B. PDA  
    C. LBA  
    D. TM only  

55. Stress testing aims to:  
    A. Verify UI design  
    B. Push system beyond normal operational limits to see failure behavior  
    C. Replace unit testing  
    D. Test only databases  

56. Number of subsets of a set with 9 elements is:  
    A. 81  
    B. 128  
    C. 256  
    D. 512  

57. BFS is optimal (in terms of number of steps) when:  
    A. All step costs are equal  
    B. Costs vary arbitrarily  
    C. Heuristic is admissible  
    D. Heuristic is consistent  

58. A language is recursive (decidable) if:  
    A. Some TM accepts members and never halts on non-members  
    B. Some TM halts on all inputs with yes/no answer  
    C. Some DFA accepts it  
    D. Some PDA accepts it  

59. High cohesion plus low coupling is desirable because:  
    A. It maximizes global variables  
    B. It increases complexity  
    C. It improves modularity and maintainability  
    D. It makes testing impossible  

60. TCP flow control prevents:  
    A. Sender from overrunning receiver’s buffer  
    B. All packet loss in network  
    C. DNS failures  
    D. IP fragmentation  

61. In C, integer expression `10 / 3 * 3` evaluates to:  
    A. 10  
    B. 9  
    C. 3  
    D. 0  

62. Height of a complete binary tree with n nodes is Θ:  
    A. 1  
    B. log n  
    C. n  
    D. n log n  

63. 2NF specifically eliminates:  
    A. Transitive dependencies  
    B. Partial dependencies of non-key on part of composite key  
    C. All non-key attributes  
    D. Foreign keys  

64. Context switching overhead increases when:  
    A. Context switches are very frequent  
    B. Process states are very small  
    C. Only one process exists  
    D. CPU is idle  

65. Induction proof usually has base case P(1) and step:  
    A. P(k) ⇒ P(k+1)  
    B. ¬P(k) ⇒ P(k+1)  
    C. P(k+1) ⇒ P(k)  
    D. P(0) ⇒ P(1) only  

66. `{ a^n b^n c^n | n ≥ 0 }` is a classic example of:  
    A. Regular language  
    B. Non-context-free language  
    C. Deterministic CFL  
    D. Finite language  

67. Black-box testing ignores:  
    A. Code structure and internal implementation  
    B. Input-output behavior  
    C. Requirements  
    D. Performance  

68. UDP is preferred over TCP when:  
    A. Reliability is more important than latency  
    B. Low latency is critical and some loss is acceptable  
    C. File transfers require integrity  
    D. Banking transactions are processed  

69. In C, `volatile` is used because variable:  
    A. Is constant  
    B. May change due to external events (e.g., hardware, another thread)  
    C. Is on disk  
    D. Is function-local  

70. Dijkstra’s algorithm works correctly for shortest paths when:  
    A. Edge weights may be negative  
    B. All edge weights are non-negative  
    C. Graph is unweighted  
    D. Graph is acyclic only  

71. Regular languages are closed under:  
    A. Union  
    B. Intersection  
    C. Complement  
    D. All of the above  

72. Acceptance testing is used to:  
    A. Verify low-level algorithms  
    B. Ensure system meets user/business requirements  
    C. Compile the code  
    D. Replace integration testing  

73. A router operates mainly at OSI layer:  
    A. 1  
    B. 2  
    C. 3  
    D. 4  

74. Aging technique in scheduling:  
    A. Decreases waiting process priorities  
    B. Increases waiting process priorities to reduce starvation  
    C. Reduces frame sizes  
    D. Eliminates deadlock  

75. A tree with n vertices is characterized by:  
    A. Being connected and acyclic with n-1 edges  
    B. Having exactly one cycle  
    C. Being disconnected  
    D. Always being complete  

---

## Questions 76–100

76. `C(7,2)` equals:  
    A. 7  
    B. 14  
    C. 21  
    D. 28  

77. DFS on an infinite tree without depth limit may:  
    A. Fail to find existing shallow solutions  
    B. Always terminate  
    C. Always find optimal paths  
    D. Be equivalent to BFS  

78. Recursively enumerable (RE) languages are:  
    A. Exactly the regular languages  
    B. Those accepted by some TM that halts on members and may loop on non-members  
    C. Those decided by a TM that halts on all inputs  
    D. Exactly CFLs  

79. Low coupling between modules means:  
    A. Modules depend heavily on each other  
    B. Changes in one module have minimal impact on others  
    C. Modules share many global variables  
    D. Modules must be tested together only  

80. TCP congestion control attempts to:  
    A. Prevent receiver overflow  
    B. Prevent network congestion collapse  
    C. Guarantee zero packet loss  
    D. Replace routing algorithms  

81. In C, integer expression `11 / 5 * 5` is:  
    A. 11  
    B. 10  
    C. 5  
    D. 0  

82. A complete binary tree property:  
    A. Every internal node has exactly two children  
    B. All levels filled except possibly last, which is filled from left  
    C. All leaves at same depth  
    D. It is always perfect  

83. 3NF removes:  
    A. Transitive dependencies where non-key depends on non-key via key  
    B. All functional dependencies  
    C. All candidate keys  
    D. All partial dependencies  

84. Context switch overhead is minimized when:  
    A. Switching infrequently and keeping PCB small  
    B. Switching very frequently  
    C. Using as many processes as possible  
    D. Avoiding time-sharing  

85. With induction, from P(1) and P(k) ⇒ P(k+1), we conclude:  
    A. P(n) for all n≥1  
    B. P(n) for some n  
    C. P(n) for even n only  
    D. Nothing  

86. DFA vs PDA:  
    A. DFA is more powerful  
    B. PDA is more powerful (can recognize all regular and more: CFLs)  
    C. They are equivalent  
    D. PDA recognizes only regular languages  

87. System testing validates:  
    A. Individual units  
    B. Integrated system against full set of requirements  
    C. Only performance  
    D. Only security  

88. UDP is suitable for:  
    A. Video/voice streaming with tolerance for some loss  
    B. Bank transfers  
    C. File sync  
    D. Database commit protocols  

89. `register` keyword (legacy C) suggests:  
    A. Variable should be stored in CPU register for speed  
    B. Variable is constant  
    C. Variable is on disk  
    D. Variable is globally visible  

90. Prim’s algorithm for MST:  
    A. Picks edges in increasing weight order anywhere  
    B. Grows a tree from a starting vertex by always adding minimum edge incident to tree  
    C. Uses union-find on all edges  
    D. Requires DAG  

91. Regular languages are closed under:  
    A. Reversal  
    B. Homomorphism  
    C. Difference (via complement and intersection)  
    D. All of the above  

92. Acceptance testing success usually means:  
    A. System is accepted by client as meeting stated requirements  
    B. No bugs exist  
    C. Code is perfectly optimized  
    D. 100% coverage is achieved  

93. Routers primarily use which address for forwarding decisions?  
    A. MAC address  
    B. IP address  
    C. Port number  
    D. Hostname  

94. Starvation can be mitigated by:  
    A. Ignoring low-priority processes  
    B. Aging and fair scheduling policies  
    C. Using only priority scheduling without aging  
    D. Reducing quantum to zero  

95. A tree with n vertices and n-1 edges that is disconnected is:  
    A. Still a tree  
    B. A forest, not a single tree  
    C. Complete  
    D. Cycle graph  

96. Turing machines are strictly more powerful than DFA because:  
    A. They can simulate finite automata and add unbounded memory via tape  
    B. They are faster  
    C. They are deterministic  
    D. They have fewer states  

97. Non-functional requirement example:  
    A. “System shall generate invoice”  
    B. “System shall record attendance”  
    C. “System shall be available 24/7 with 99.9% uptime”  
    D. “System shall support user login”  

98. DHCP’s role in IP networks is to:  
    A. Dynamically assign IP configuration to hosts  
    B. Resolve domain names  
    C. Map IP to MAC  
    D. Perform ARP  

99. Which language over `{0,1}` is regular?  
    A. `{ 0^n 1^n | n ≥ 0 }`  
    B. `{ w | w has the same number of 0s and 1s }`  
    C. `{ w | w has at most one 1 }`  
    D. `{ w w | w ∈ {0,1}* }`  

100. In no-negative-marking MCQ tests, best practice is to:  
     A. Skip any question you’re not sure of  
     B. Use elimination and then guess among remaining options  
     C. Answer only 50% questions  
     D. Attempt only numerical ones  

---

## Answer Key – Mock Test 5

| Q | Ans | Q | Ans | Q | Ans | Q | Ans |
|---|---|---|---|---|---|---|---|
| 1 | C | 26 | B | 51 | B | 76 | C |
| 2 | B | 27 | B | 52 | B | 77 | A |
| 3 | A | 28 | B | 53 | B | 78 | B |
| 4 | B | 29 | B | 54 | A | 79 | B |
| 5 | D | 30 | B | 55 | B | 80 | B |
| 6 | B | 31 | B | 56 | D | 81 | B |
| 7 | A | 32 | A | 57 | A | 82 | B |
| 8 | B | 33 | A | 58 | B | 83 | A |
| 9 | A | 34 | B | 59 | C | 84 | A |
|10 | B | 35 | B | 60 | A | 85 | A |
|11 | B | 36 | B | 61 | B | 86 | B |
|12 | A | 37 | C | 62 | B | 87 | B |
|13 | B | 38 | B | 63 | B | 88 | A |
|14 | B | 39 | A | 64 | A | 89 | A |
|15 | B | 40 | B | 65 | A | 90 | B |
|16 | C | 41 | B | 66 | B | 91 | D |
|17 | C | 42 | A | 67 | A | 92 | A |
|18 | C | 43 | B | 68 | B | 93 | B |
|19 | B | 44 | A | 69 | B | 94 | B |
|20 | C | 45 | B | 70 | B | 95 | B |
|21 | C | 46 | A | 71 | D | 96 | A |
|22 | C | 47 | B | 72 | B | 97 | C |
|23 | B | 48 | A | 73 | C | 98 | A |
|24 | C | 49 | B | 74 | B | 99 | C |
|25 | A | 50 | B | 75 | A |100 | B |

### Notes

- All core FAST computing subjects (PF, OOP, DSA, Discrete, DB, OS, Automata, AI, Networks, SE) appear multiple times, consistent with the BS CS curriculum’s stated learning outcomes in programming, data structures, operating systems, databases, AI, networking, and software engineering.[web:48][web:32]  
- Many items are designed to hit common traps: undefined behavior in C, subtle operator precedence, deadlock conditions, pumping lemma usage, regular vs CFL classification, and closure properties.
