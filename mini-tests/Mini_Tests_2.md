

This part continues the crash course with:
- Daily Mini Tests (Days 4–6)
- Full-Length Mock Test 1 (100 MCQs)

> FAST’s published BS Computer Science curriculum includes Programming Fundamentals, Object-Oriented Programming, Data Structures, Discrete Structures, Database Systems, Operating Systems, Theory of Automata, Artificial Intelligence, Computer Networks, and Software Engineering, which matches the subject mix used in this handbook and the full mock design below.[web:19]

> FAST Karachi also publicly advertised faculty positions in Computing and AI in 2026, which supports using a broad, instructor-level computing coverage rather than a narrow single-subject prep strategy.[web:65]

---

## Daily Mini Tests

## Day 4 Mini Test

### Questions

1. Overriding is associated mainly with:  
   A. Compile-time polymorphism  
   B. Run-time polymorphism  
   C. SQL optimization  
   D. Paging

2. Which sorting algorithm is in-place and has `O(n log n)` worst-case time?  
   A. Merge sort  
   B. Heap sort  
   C. Insertion sort  
   D. Bubble sort

3. Which key uniquely identifies tuples but must be minimal to qualify?  
   A. Super key  
   B. Candidate key  
   C. Foreign key  
   D. Alternate route key

4. Thrashing is closely associated with:  
   A. Excessive paging  
   B. Deadlock prevention  
   C. CPU overclocking  
   D. Database joins

5. Which relation property means `(a,b)` and `(b,a)` together imply `a=b`?  
   A. Symmetric  
   B. Reflexive  
   C. Antisymmetric  
   D. Transitive

6. Which search is complete and optimal for non-negative path costs without heuristic?  
   A. DFS  
   B. Uniform Cost Search  
   C. Greedy Best-First  
   D. Hill climbing

7. Which statement about pumping lemma is correct?  
   A. It proves a language is regular  
   B. It is used mostly to disprove regularity  
   C. It applies only to finite languages  
   D. It minimizes DFA

8. Which testing type is closest to checking one function/class in isolation?  
   A. System testing  
   B. Unit testing  
   C. Acceptance testing  
   D. Beta deployment

9. Which protocol is commonly used for email transfer between servers?  
   A. SMTP  
   B. FTP  
   C. ARP  
   D. DHCP

10. Which expression is dangerous because `x` may be incremented unexpectedly only if the left part is evaluated?  
    A. `a + b`  
    B. `a && x++`  
    C. `a * b`  
    D. `a - b`

11. Which graph algorithm is used for minimum spanning tree?  
    A. Kruskal  
    B. Binary search  
    C. Inorder traversal  
    D. Regex conversion

12. Which SQL operation combines rows from two relations based on a matching condition?  
    A. Projection  
    B. Selection  
    C. Join  
    D. Division only

13. A semaphore with value 1 behaves most similarly to a:  
    A. Queue  
    B. Mutex-style lock  
    C. Page table  
    D. Hash function

14. Which proof technique assumes the negation of the desired conclusion?  
    A. Direct proof  
    B. Proof by contradiction  
    C. Mathematical induction only  
    D. Enumeration only

15. Which heuristic-based algorithm is not guaranteed optimal in general?  
    A. Uniform Cost Search  
    B. BFS with unit costs  
    C. Greedy Best-First Search  
    D. A* with admissible heuristic

16. Which automaton naturally recognizes balanced parentheses?  
    A. DFA  
    B. PDA  
    C. NFA only without stack  
    D. Hash automaton

17. Which requirement is “the app should support 10,000 concurrent users”?  
    A. Functional  
    B. Non-functional  
    C. Use case  
    D. User story only

18. Which protocol provides reliable byte-stream communication?  
    A. UDP  
    B. IP  
    C. TCP  
    D. ARP

19. If a function receives an argument by value, changes inside the function:  
    A. Always modify the caller’s variable  
    B. Modify only the local copy  
    C. Cause stack corruption  
    D. Are impossible

20. In a BST, keys in the left subtree are generally:  
    A. Greater than root  
    B. Equal to every right key  
    C. Less than root  
    D. Unordered

### Answers and Explanations

1. **B** — Overriding is a run-time polymorphism mechanism.  
2. **B** — Heap sort is in-place and worst-case `O(n log n)`.  
3. **B** — Candidate key is a minimal super key.  
4. **A** — Thrashing means time is lost handling too many page swaps.  
5. **C** — That is the definition of antisymmetry.  
6. **B** — Uniform Cost Search is optimal with non-negative costs.  
7. **B** — Pumping lemma is usually used to prove non-regularity.  
8. **B** — Unit testing isolates a small code unit.  
9. **A** — SMTP handles mail transfer.  
10. **B** — Short-circuit logic may skip or trigger side effects based on the first operand.  
11. **A** — Kruskal is a classic MST algorithm.  
12. **C** — Join combines related rows from different relations.  
13. **B** — A binary semaphore behaves similarly to a mutual exclusion control.  
14. **B** — Contradiction starts from assuming the opposite.  
15. **C** — Greedy Best-First is not generally optimal.  
16. **B** — Balanced nesting is naturally handled by a stack.  
17. **B** — Concurrency capacity is a quality constraint.  
18. **C** — TCP provides reliable ordered delivery.  
19. **B** — Pass by value affects only the local copy.  
20. **C** — BST left subtree contains smaller keys under the standard ordering rule.

---

## Day 5 Mini Test

### Questions

1. Which OOP relationship represents “has-a”?  
   A. Inheritance  
   B. Composition  
   C. Overriding  
   D. Recursion

2. The average search complexity in a balanced BST is:  
   A. `O(1)`  
   B. `O(log n)`  
   C. `O(n)`  
   D. `O(n log n)`

3. Which isolation issue means a row read twice gives different committed values?  
   A. Dirty read  
   B. Non-repeatable read  
   C. Phantom power  
   D. Deadlock

4. Which scheduling strategy may minimize average waiting time if burst lengths are known?  
   A. SJF  
   B. FCFS  
   C. RR  
   D. FIFO replacement

5. Which function property means one-to-one?  
   A. Surjective  
   B. Reflexive  
   C. Injective  
   D. Symmetric

6. Which AI method starts from facts and derives consequences?  
   A. Backward chaining  
   B. Forward chaining  
   C. Hill climbing  
   D. Topological reasoning

7. Which statement is true about regular expressions?  
   A. They define all context-free languages  
   B. They define exactly regular languages  
   C. They require stacks  
   D. They are stronger than Turing machines

8. Which software maintenance type fixes bugs after delivery?  
   A. Corrective  
   B. Adaptive  
   C. Perfective  
   D. Preventive

9. Which device forwards packets between different IP networks?  
   A. Hub  
   B. Switch  
   C. Router  
   D. NIC only

10. Which statement about `do-while` is correct?  
    A. It checks condition before first iteration  
    B. It always executes at least once  
    C. It cannot contain `break`  
    D. It cannot be nested

11. Which sorting method is stable and divide-and-conquer based?  
    A. Merge sort  
    B. Heap sort  
    C. Selection sort  
    D. Shell sort only

12. Which dependency type violates 2NF?  
    A. Partial dependency on a composite key  
    B. No dependency at all  
    C. Candidate key dependency  
    D. Referential dependency only

13. Which page replacement algorithm replaces the least recently used page?  
    A. FIFO  
    B. LRU  
    C. Optimal impossible by definition  
    D. SRTF

14. A graph with no cycles and connected structure is a:  
    A. Clique  
    B. Tree  
    C. DAG necessarily directed  
    D. Multigraph

15. Which search strategy expands shallowest nodes first?  
    A. DFS  
    B. BFS  
    C. Greedy  
    D. Hill climbing

16. `{ a^n b^n | n >= 0 }` is:  
    A. Regular  
    B. Context-free but not regular  
    C. Not context-free  
    D. Finite

17. Which testing type checks the whole integrated application against system requirements?  
    A. Unit  
    B. Integration  
    C. System  
    D. Static analysis only

18. Which protocol is connectionless?  
    A. TCP  
    B. UDP  
    C. HTTP as transport  
    D. SMTP as transport

19. Which common bug arises from accessing index `n` in an array of size `n`?  
    A. Deadlock  
    B. Off-by-one / out-of-bounds  
    C. Serialization  
    D. Ambiguity

20. Which notation gives an asymptotic upper bound?  
    A. Big-O  
    B. Big-Omega  
    C. Big-Theta only lower  
    D. Little-alpha

### Answers and Explanations

1. **B** — Composition models a has-a relationship.  
2. **B** — Balanced BST height is logarithmic.  
3. **B** — A second read seeing a different committed value is non-repeatable read.  
4. **A** — SJF is optimal for average waiting time when burst times are known.  
5. **C** — Injective means distinct inputs map to distinct outputs.  
6. **B** — Forward chaining moves from facts to conclusions.  
7. **B** — Regex captures exactly regular languages.  
8. **A** — Corrective maintenance removes faults.  
9. **C** — Router forwards across networks using IP.  
10. **B** — `do-while` executes once before checking its condition.  
11. **A** — Merge sort is a stable divide-and-conquer algorithm.  
12. **A** — Partial dependency violates 2NF.  
13. **B** — LRU selects the least recently used page.  
14. **B** — A connected acyclic graph is a tree.  
15. **B** — BFS explores level by level.  
16. **B** — It requires stack-like memory but remains context-free.  
17. **C** — System testing evaluates the integrated full system.  
18. **B** — UDP is connectionless.  
19. **B** — Valid indices are usually `0` to `n-1`.  
20. **A** — Big-O denotes an asymptotic upper bound.

---

## Day 6 Mini Test

### Questions

1. Which feature enables dynamic dispatch in C++-style OOP?  
   A. Inline function  
   B. Virtual function  
   C. Macro expansion  
   D. Constant folding

2. Which graph traversal naturally uses a queue?  
   A. DFS  
   B. BFS  
   C. Topological sort only by stack  
   D. Inorder traversal

3. Which SQL keyword removes duplicate rows from output?  
   A. UNIQUE  
   B. DISTINCT  
   C. FILTER  
   D. INDEX

4. Which deadlock condition can be broken by forcing resource ordering?  
   A. Circular wait  
   B. Mutual exclusion  
   C. No scheduling  
   D. Page fault

5. Which relation property means every element relates to itself?  
   A. Symmetric  
   B. Reflexive  
   C. Transitive  
   D. Bijective

6. Which search algorithm may be memory intensive because it keeps a frontier of shallow layers?  
   A. BFS  
   B. DFS  
   C. Hill climbing  
   D. Greedy always uses less memory by theorem

7. Which statement about Turing machines is correct?  
   A. They recognize only regular languages  
   B. They are weaker than PDA  
   C. They model a more powerful general computation mechanism  
   D. They cannot simulate DFA

8. Which SDLC artifact is produced during requirements analysis?  
   A. SRS  
   B. Executable binary  
   C. Routing table  
   D. Stack frame

9. Which layer is associated with MAC addressing?  
   A. Network  
   B. Transport  
   C. Data Link  
   D. Session

10. Which statement about integer overflow in fixed-size types is safest in MCQ reasoning?  
    A. It never happens  
    B. It depends on representation/language rules and can produce unexpected results  
    C. It always throws an exception  
    D. It automatically converts to float

11. Which data structure is best for repeatedly extracting minimum priority element?  
    A. Heap  
    B. Array unsorted only  
    C. Linked list tail  
    D. Trie

12. Which normal form is stricter than 3NF?  
    A. 1NF  
    B. 2NF  
    C. BCNF  
    D. DNF

13. Which mode allows privileged instructions?  
    A. User mode  
    B. Kernel mode  
    C. Thread-local mode  
    D. Protected loop mode

14. If a function is both injective and surjective, it is:  
    A. Reflexive  
    B. Bijective  
    C. Symmetric  
    D. Partial

15. Which algorithm is used to convert an NFA conceptually into an equivalent DFA?  
    A. Prim’s algorithm  
    B. Subset construction  
    C. Dynamic programming  
    D. Huffman coding

16. Which design principle is preferred?  
    A. High coupling and low cohesion  
    B. Low cohesion and high complexity  
    C. High cohesion and low coupling  
    D. High coupling and duplication

17. Which protocol is commonly used to fetch web pages securely?  
    A. FTP  
    B. HTTP only on UDP  
    C. HTTPS  
    D. ARP

18. Which statement about recursion and iteration is correct?  
    A. Recursion never uses stack frames  
   B. Iteration always uses more memory  
    C. Recursion can often be converted into iteration for many problems  
    D. They are unrelated paradigms

19. Which language class is recognized by PDA?  
    A. Regular only  
    B. Context-free languages  
    C. All recursively enumerable languages  
    D. Only finite languages

20. Which of the following is a software quality attribute rather than a function?  
    A. User can log in  
    B. System sends invoice  
    C. Response time under 2 seconds  
    D. Generate salary slip

### Answers and Explanations

1. **B** — Virtual functions support run-time dispatch.  
2. **B** — BFS uses a queue to process frontier in layers.  
3. **B** — `DISTINCT` removes duplicate result rows.  
4. **A** — Resource ordering breaks circular wait.  
5. **B** — Reflexive means every element relates to itself.  
6. **A** — BFS stores broad frontier layers and may consume a lot of memory.  
7. **C** — Turing machines are the standard powerful abstract computation model here.  
8. **A** — Requirements analysis produces an SRS.  
9. **C** — MAC addressing is a data-link concern.  
10. **B** — Overflow behavior depends on the language and representation rules, and is often a trap.  
11. **A** — Heap efficiently supports priority extraction.  
12. **C** — BCNF is stronger than 3NF.  
13. **B** — Privileged instructions require kernel mode.  
14. **B** — One-to-one plus onto gives bijection.  
15. **B** — Subset construction builds DFA states from sets of NFA states.  
16. **C** — High cohesion and low coupling is preferred design.  
17. **C** — HTTPS is the standard secure web protocol.  
18. **C** — Many recursive procedures can be rewritten iteratively.  
19. **B** — PDA recognizes context-free languages.  
20. **C** — Response time is a non-functional quality attribute.

---
