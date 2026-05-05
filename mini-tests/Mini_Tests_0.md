# FAST School of Computing (Karachi Campus) Instructor Screening Test Crash Course

## Part 4

This part continues the crash course with:
- Software Engineering
- Computer Networks
- Daily Mini Tests

> FAST’s BS Computer Science curriculum explicitly includes Software Engineering and Computer Networks as core courses, which makes them highly likely screening areas for a School of Computing instructor role.[web:19]

---

## Software Engineering

### High-Yield Topics

- Software process models: Waterfall, Incremental, Spiral, Agile
- Requirements engineering: functional vs non-functional requirements
- Software design principles: cohesion, coupling, modularity
- UML basics: use case, class, sequence, activity diagrams
- Testing: unit, integration, system, acceptance, regression
- Verification vs validation
- Maintenance types: corrective, adaptive, perfective, preventive
- Risk management and software quality basics

### Revision Notes

#### Core Definitions

| Term | Meaning |
|---|---|
| Functional requirement | What the system should do |
| Non-functional requirement | Quality constraints such as performance or security |
| Cohesion | Relatedness of responsibilities within a module |
| Coupling | Interdependence between modules |
| Verification | Building the product right |
| Validation | Building the right product |

#### Process Model Comparison

| Model | Best Used When | Limitation |
|---|---|---|
| Waterfall | Requirements are stable | Poor flexibility to change |
| Incremental | Delivery in parts is useful | Integration planning needed |
| Spiral | Risk is high | More management complexity |
| Agile | Requirements evolve rapidly | Needs active customer collaboration |

#### Testing Comparison

| Testing Type | Focus |
|---|---|
| Unit testing | Individual component |
| Integration testing | Interaction among modules |
| System testing | Entire integrated system |
| Acceptance testing | Customer/business acceptance |
| Regression testing | Ensure changes did not break old behavior |

> Common trap: Verification and validation are not synonyms. MCQs often swap them deliberately.

#### Memory Tricks

- High cohesion, low coupling
- Verification = right product built right
- Validation = right thing built
- Regression = re-check after change

### Practice MCQs

#### MCQ 1

Which process model is most suitable when requirements are stable and well understood early?

A. Agile  
B. Spiral  
C. Waterfall  
D. Prototype-only model

**Answer:** C  
**Explanation:** Waterfall fits projects with clear, stable requirements and limited expected change.

#### MCQ 2

Which pair is generally considered desirable in software design?

A. Low cohesion, high coupling  
B. High cohesion, low coupling  
C. High cohesion, high coupling  
D. Low cohesion, low abstraction

**Answer:** B  
**Explanation:** Modules should be internally focused and minimally dependent on others.

#### MCQ 3

Which testing level focuses primarily on interfaces among modules?

A. Unit testing  
B. Integration testing  
C. Acceptance testing  
D. Mutation testing only

**Answer:** B  
**Explanation:** Integration testing checks whether combined components interact correctly.

#### MCQ 4

A requirement such as “the system should respond within 2 seconds” is:

A. Functional requirement  
B. Non-functional requirement  
C. Design pattern  
D. Test case

**Answer:** B  
**Explanation:** It specifies a performance constraint, not a specific system function.

#### MCQ 5

Which statement best describes regression testing?

A. Testing only before the first release  
B. Testing after modifications to ensure existing features still work  
C. Testing only database schema  
D. Testing by end users only

**Answer:** B  
**Explanation:** Regression testing protects against unintended side effects of change.

#### MCQ 6

“Are we building the product right?” refers to:

A. Validation  
B. Verification  
C. Maintenance  
D. Refactoring

**Answer:** B  
**Explanation:** Verification checks conformance to specification and design intent.

#### MCQ 7

Which maintenance category adapts software to a changed environment?

A. Corrective  
B. Perfective  
C. Adaptive  
D. Preventive

**Answer:** C  
**Explanation:** Adaptive maintenance handles changes in platform, regulations, environment, or dependencies.

#### MCQ 8

A use case diagram is primarily used to capture:

A. Data structure balancing rules  
B. User interactions and system goals  
C. Thread scheduling policy  
D. TCP congestion windows

**Answer:** B  
**Explanation:** Use cases focus on actors and the services they expect from the system.

### Summary Sheet

- Memorize process models, testing levels, and requirement categories.
- Be precise about cohesion, coupling, verification, and validation.
- Expect scenario-based MCQs rather than memorization-only questions.

---

## Computer Networks

### High-Yield Topics

- OSI and TCP/IP layers and mapping
- Switching: circuit switching vs packet switching
- TCP vs UDP
- IP addressing basics, subnet masks, routing intuition
- ARP, DNS, DHCP, NAT basics
- Reliable transport, flow control, congestion control
- Error detection basics: parity, checksum, CRC
- Common protocols: HTTP, HTTPS, FTP, SMTP, POP3, IMAP, DNS
- Devices: hub, switch, router, gateway

### Revision Notes

#### Layer Mapping

| OSI Layer | Main Responsibility |
|---|---|
| Application | End-user network services |
| Presentation | Data representation, translation |
| Session | Session management |
| Transport | End-to-end delivery |
| Network | Logical addressing and routing |
| Data Link | Framing, MAC addressing |
| Physical | Bits on medium |

#### TCP vs UDP

| Feature | TCP | UDP |
|---|---|---|
| Connection | Connection-oriented | Connectionless |
| Reliability | Reliable | Best-effort |
| Ordering | Ordered delivery | No guarantee |
| Speed/overhead | Higher overhead | Lower overhead |
| Typical use | Web, file transfer | Streaming, DNS, gaming |

#### Device Comparison

| Device | Layer Focus | Main Role |
|---|---|---|
| Hub | Physical | Broadcast bits |
| Switch | Data Link | Forward frames using MAC |
| Router | Network | Forward packets using IP |
| Gateway | Multiple / translation | Protocol or network translation |

> Common trap: A switch is not a router. Switches typically use MAC addresses, while routers use IP addresses.

#### Memory Tricks

- TCP = reliable and ordered
- UDP = lightweight and fast
- DNS resolves names
- DHCP gives addresses
- ARP maps IP to MAC in local network context

### Practice MCQs

#### MCQ 1

Which layer is responsible for routing packets across networks?

A. Transport layer  
B. Application layer  
C. Network layer  
D. Presentation layer

**Answer:** C  
**Explanation:** Routing and logical addressing belong to the network layer.

#### MCQ 2

Which protocol is typically used to resolve domain names into IP addresses?

A. SMTP  
B. DNS  
C. ARP  
D. FTP

**Answer:** B  
**Explanation:** DNS translates hostnames into IP addresses.

#### MCQ 3

Which statement about TCP is correct?

A. It is connectionless and unreliable  
B. It provides ordered, reliable byte-stream delivery  
C. It works only on local area networks  
D. It does not perform flow control

**Answer:** B  
**Explanation:** TCP establishes a connection and provides reliable transport with ordering.

#### MCQ 4

A switch primarily forwards data based on:

A. Port number  
B. Domain name  
C. MAC address  
D. Process ID

**Answer:** C  
**Explanation:** Ethernet switches make forwarding decisions using MAC addresses.

#### MCQ 5

Which protocol dynamically assigns IP addresses to hosts?

A. DHCP  
B. DNS  
C. HTTP  
D. ARP

**Answer:** A  
**Explanation:** DHCP automates address allocation and related configuration.

#### MCQ 6

Which of the following best fits UDP use?

A. Situation requiring strict in-order guaranteed delivery  
B. File transfer requiring reliability  
C. Latency-sensitive communication where some loss is acceptable  
D. Database transaction commit protocol only

**Answer:** C  
**Explanation:** UDP is often preferred when low latency matters more than perfect reliability.

#### MCQ 7

ARP is used to:

A. Map a domain name to IP address  
B. Map an IP address to a MAC address on a local network  
C. Encrypt packets end to end  
D. Assign CPU time slices

**Answer:** B  
**Explanation:** ARP resolves a local network-layer address to link-layer hardware address.

#### MCQ 8

Which device operates mainly at the network layer?

A. Hub  
B. Router  
C. Repeater  
D. Bridge only at physical layer

**Answer:** B  
**Explanation:** Routers examine IP information to forward packets between networks.

### Summary Sheet

- Memorize layer responsibilities and common protocols.
- Rehearse TCP vs UDP, switch vs router, DNS vs DHCP vs ARP.
- Expect definition, mapping, and scenario-based protocol MCQs.

---

## Daily Mini Tests

Each mini test is mixed-subject and intended for 30–45 minutes. Try the questions first, then review the answers and explanations.

## Day 1 Mini Test

### Questions

1. Which OOP principle is most closely related to hiding internal state behind methods?  
   A. Inheritance  
   B. Encapsulation  
   C. Normalization  
   D. Routing

2. In zero-based indexing, the last valid index of an array of size `n` is:  
   A. `n`  
   B. `n+1`  
   C. `n-1`  
   D. `1`

3. Which data structure follows FIFO order?  
   A. Stack  
   B. Queue  
   C. Heap  
   D. BST

4. Which normal form removes transitive dependencies?  
   A. 1NF  
   B. 2NF  
   C. 3NF  
   D. 4NF

5. Which is a necessary condition for deadlock?  
   A. Preemption  
   B. Circular wait  
   C. Infinite memory  
   D. Encryption

6. A relation that is reflexive, symmetric, and transitive is:  
   A. Partial order  
   B. Equivalence relation  
   C. Injection  
   D. Surjection

7. Which heuristic property means it never overestimates the true cost?  
   A. Complete  
   B. Admissible  
   C. Recursive  
   D. Deterministic

8. Which pair has the same expressive power?  
   A. DFA and NFA  
   B. DFA and PDA  
   C. PDA and TM  
   D. CFG and TM

9. Which process model is best suited to changing requirements?  
   A. Waterfall  
   B. Agile  
   C. Pure batch processing  
   D. FCFS

10. Which protocol resolves hostnames to IP addresses?  
    A. ARP  
    B. DNS  
    C. SMTP  
    D. FTP

11. Integer division `9 / 4` in many languages yields:  
    A. `2`  
    B. `2.25`  
    C. `3`  
    D. Undefined always

12. Which traversal of a BST yields sorted order?  
    A. Preorder  
    B. Inorder  
    C. Postorder  
    D. Random order

13. A foreign key enforces:  
    A. Referential integrity  
    B. Thread safety  
    C. Encapsulation  
    D. Compression

14. Which scheduling algorithm uses a time quantum?  
    A. FCFS  
    B. RR  
    C. SJF  
    D. Priority only

15. Number of subsets of a 4-element set is:  
    A. 4  
    B. 8  
    C. 16  
    D. 24

16. Which search uses `f(n) = g(n) + h(n)`?  
    A. BFS  
    B. DFS  
    C. A*  
    D. Greedy only by `h`

17. Which language is not regular?  
    A. Strings with even number of `0`s  
    B. `a* b*`  
    C. `{ a^n b^n | n >= 0 }`  
    D. Finite language over `{a,b}`

18. Which testing type checks interactions among modules?  
    A. Unit  
    B. Integration  
    C. Acceptance  
    D. Mutation only

19. Which device forwards frames using MAC addresses?  
    A. Router  
    B. Switch  
    C. Gateway only  
    D. DNS server

20. Which loop always executes at least once?  
    A. `for`  
    B. `while`  
    C. `do-while`  
    D. None of these

### Answers and Explanations

1. **B** — Encapsulation hides state and exposes controlled access.  
2. **C** — Zero-based arrays run from `0` to `n-1`.  
3. **B** — Queue is FIFO.  
4. **C** — 3NF removes transitive dependency.  
5. **B** — Circular wait is one of the four deadlock conditions.  
6. **B** — That exact property triple defines equivalence relation.  
7. **B** — Admissible heuristics do not overestimate.  
8. **A** — DFA and NFA recognize exactly regular languages.  
9. **B** — Agile is designed for evolving requirements.  
10. **B** — DNS resolves names into IP addresses.  
11. **A** — Integer division truncates the fraction.  
12. **B** — Inorder traversal of BST gives sorted sequence.  
13. **A** — Foreign keys maintain valid references across relations.  
14. **B** — Round Robin allocates CPU by fixed time quantum.  
15. **C** — Number of subsets is `2^4 = 16`.  
16. **C** — A* combines path cost and heuristic.  
17. **C** — Matching equal counts of `a` and `b` is not regular.  
18. **B** — Integration testing targets interactions among modules.  
19. **B** — Switches operate using MAC addresses.  
20. **C** — `do-while` checks condition after first execution.

---

## Day 2 Mini Test

### Questions

1. Which parameter passing method modifies the caller’s original object most directly?  
   A. Pass by value  
   B. Pass by reference  
   C. Pass by copy-return only  
   D. Pass by random access

2. Worst-case time complexity of quicksort is:  
   A. `O(log n)`  
   B. `O(n)`  
   C. `O(n log n)`  
   D. `O(n^2)`

3. Which SQL clause filters grouped results?  
   A. WHERE  
   B. HAVING  
   C. DISTINCT  
   D. JOIN

4. Which page replacement algorithm may show Belady’s anomaly?  
   A. FIFO  
   B. LRU  
   C. Optimal  
   D. MRU

5. In a tree with `n` vertices, number of edges is:  
   A. `n`  
   B. `n-1`  
   C. `n+1`  
   D. `2n`

6. Which learning type uses unlabeled data?  
   A. Supervised  
   B. Reinforcement  
   C. Unsupervised  
   D. Rule-based only

7. Which machine naturally recognizes context-free languages?  
   A. DFA  
   B. PDA  
   C. TM only for regular languages  
   D. Queue automaton only

8. Which requirement type specifies response time?  
   A. Functional  
   B. Non-functional  
   C. Algorithmic complexity  
   D. Class inheritance

9. Which protocol dynamically assigns IP configuration?  
   A. DNS  
   B. DHCP  
   C. HTTP  
   D. SMTP

10. Which statement about recursion is essential?  
    A. It cannot use local variables  
    B. It must have a base case  
    C. It is always faster than iteration  
    D. It cannot process trees

11. Which structure supports LIFO?  
    A. Queue  
    B. Stack  
    C. Heap  
    D. Graph

12. Which key is a minimal super key?  
    A. Foreign key  
    B. Candidate key  
    C. Secondary key  
    D. Index key only

13. Threads in the same process usually share:  
    A. Program counter only  
    B. Address space  
    C. Stack only  
    D. Independent page tables only

14. Which function property means “onto”?  
    A. Injective  
    B. Surjective  
    C. Reflexive  
    D. Symmetric

15. Which search is optimal for non-negative weighted edges from one source?  
    A. BFS always  
    B. DFS  
    C. Dijkstra  
    D. Topological sorting

16. Which statement about NFA is true?  
    A. It is more powerful than DFA  
    B. It may have multiple possible next states on a symbol  
    C. It cannot recognize infinite languages  
    D. It requires a stack

17. Verification asks:  
    A. Are we building the right product?  
    B. Are we building the product right?  
    C. Is the packet routed right?  
    D. Is the heuristic admissible?

18. Which layer handles end-to-end delivery?  
    A. Data link  
    B. Physical  
    C. Transport  
    D. Session only

19. Which statement about local variables in C/C++ is generally true?  
    A. Always initialized to zero  
    B. Always null  
    C. May contain indeterminate value if uninitialized  
    D. Stored only in heap

20. Which graph traversal explores level by level?  
    A. DFS  
    B. BFS  
    C. Dijkstra only  
    D. Inorder

### Answers and Explanations

1. **B** — Reference-style passing can directly affect caller state.  
2. **D** — Quicksort degrades to quadratic time with poor pivots.  
3. **B** — `HAVING` filters after grouping.  
4. **A** — FIFO may show Belady’s anomaly.  
5. **B** — Tree edge count is `n-1`.  
6. **C** — Unsupervised learning uses unlabeled data.  
7. **B** — PDA is the classic recognizer for CFLs.  
8. **B** — Response time is a quality constraint.  
9. **B** — DHCP assigns IP configuration.  
10. **B** — Base case prevents infinite recursion.  
11. **B** — Stack is LIFO.  
12. **B** — Candidate key is a minimal super key.  
13. **B** — Threads share address space within a process.  
14. **B** — Surjective means onto.  
15. **C** — Dijkstra is standard for non-negative weighted edges.  
16. **B** — NFA can branch nondeterministically.  
17. **B** — Verification checks correctness of the build process against specification.  
18. **C** — Transport layer provides end-to-end delivery.  
19. **C** — Uninitialized locals may contain garbage values.  
20. **B** — BFS explores level by level.

---

## Day 3 Mini Test

### Questions

1. Which operator pair commonly supports short-circuit evaluation?  
   A. `+` and `-`  
   B. `&&` and `||`  
   C. `*` and `/`  
   D. `%` and `^`

2. Which sort is stable in its standard textbook array implementation?  
   A. Heap sort  
   B. Merge sort  
   C. Selection sort always  
   D. Quick sort always

3. Which anomaly means reading uncommitted data?  
   A. Dirty read  
   B. Lost update  
   C. Deadlock  
   D. Thrashing

4. Which scheduling algorithm may starve low-priority jobs without aging?  
   A. FCFS  
   B. Priority scheduling  
   C. RR  
   D. FIFO page replacement

5. A bijection is:  
   A. One-to-one only  
   B. Onto only  
   C. Both one-to-one and onto  
   D. Always symmetric

6. Greedy Best-First Search mainly uses:  
   A. `g(n)` only  
   B. `h(n)` only  
   C. `g(n) + h(n)`  
   D. Path depth only

7. Which statement about `{ a^n b^n c^n | n >= 0 }` is correct?  
   A. It is regular  
   B. It is context-free  
   C. It is not context-free  
   D. It is finite

8. Which maintenance improves performance or usability without correcting faults?  
   A. Corrective  
   B. Adaptive  
   C. Perfective  
   D. Preventive only by patching bugs

9. Which device works mainly with IP forwarding?  
   A. Switch  
   B. Router  
   C. Hub  
   D. Bridge at physical layer

10. Which loop-control bug often skips exactly one intended iteration or accesses one extra element?  
    A. Deadlock  
    B. Off-by-one error  
    C. Livelock  
    D. Starvation

11. Which tree structure is optimized for priority retrieval?  
    A. BST  
    B. Heap  
    C. Trie  
    D. Parse tree

12. Which SQL join returns only matching tuples?  
    A. Inner join  
    B. Left outer join  
    C. Right outer join  
    D. Full outer join

13. Which issue arises when concurrent execution order changes final outcome unsafely?  
    A. Race condition  
    B. Segmentation  
    C. Serialization  
    D. Compression

14. Which statement is true for a finite language?  
    A. It may be non-regular  
    B. It is always regular  
    C. It requires PDA  
    D. It is never context-free

15. Which testing type is performed by users or customers against requirements?  
    A. Unit testing  
    B. Acceptance testing  
    C. White-box testing only  
    D. Refactoring

16. Which protocol maps local IP addresses to MAC addresses?  
    A. DNS  
    B. ARP  
    C. FTP  
    D. POP3

17. Which statement about binary search is correct?  
    A. It works on any unsorted array  
    B. It requires sorted search space  
    C. It is always O(1)  
    D. It is equivalent to hashing

18. Number of subsets of a set with `n` elements is:  
    A. `n!`  
    B. `n^2`  
    C. `2^n`  
    D. `n(n-1)/2`

19. Which heuristic property implies non-overestimation and helps A* optimality?  
    A. Admissibility  
    B. Ambiguity  
    C. Transitivity  
    D. Serializability

20. Which automaton has finite control and no stack or tape memory beyond state?  
    A. PDA  
    B. TM  
    C. DFA  
    D. Pushdown transducer only

### Answers and Explanations

1. **B** — Logical AND and OR commonly short-circuit.  
2. **B** — Merge sort is stable in standard form.  
3. **A** — Dirty read is reading uncommitted data.  
4. **B** — Priority scheduling can starve low-priority tasks.  
5. **C** — Bijection means injective and surjective.  
6. **B** — Greedy uses only heuristic estimate.  
7. **C** — This classic language is not context-free.  
8. **C** — Perfective maintenance improves qualities such as performance or usability.  
9. **B** — Routers forward using network-layer addressing.  
10. **B** — Off-by-one is the classic boundary bug.  
11. **B** — Heap supports efficient min/max retrieval.  
12. **A** — Inner join keeps only matches.  
13. **A** — That is a race condition.  
14. **B** — Every finite language is regular.  
15. **B** — Acceptance testing validates fitness for intended use.  
16. **B** — ARP maps IP to MAC locally.  
17. **B** — Binary search needs sorted order.  
18. **C** — Power set size is `2^n`.  
19. **A** — Admissibility means not overestimating.  
20. **C** — DFA has only finite-state memory.

---

## Stop Point

This is **Part 4**, containing:
- Software Engineering
- Computer Networks
- Daily Mini Tests (Days 1–3)

Type **continue** for Part 5:
- Daily Mini Tests (Days 4–6)
- Full-Length Mock Test 1 (100 MCQs)
