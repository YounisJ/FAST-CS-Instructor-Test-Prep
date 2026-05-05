
## Operating Systems

### High-Yield Topics

- Process vs thread, PCB, context switching
- CPU scheduling: FCFS, SJF, SRTF, RR, priority
- Synchronization: critical section, semaphore, mutex, monitor
- Deadlocks: conditions, prevention, avoidance, detection
- Memory management: paging, segmentation, virtual memory
- Page replacement: FIFO, LRU, Optimal
- File systems, system calls, user mode vs kernel mode

### Revision Notes

#### Core Definitions

| Term | Meaning |
|---|---|
| Process | Program in execution with its own address space |
| Thread | Lightweight execution unit within a process |
| Context switch | Saving and restoring execution state |
| Semaphore | Synchronization primitive using counter |
| Deadlock | Permanent waiting cycle among processes |
| Page fault | Referenced page absent from main memory |

#### Scheduling Comparison

| Algorithm | Strength | Typical Weakness |
|---|---|---|
| FCFS | Simple | Convoy effect |
| SJF | Good average waiting time | Needs burst prediction |
| SRTF | Better responsiveness than SJF | Higher overhead |
| RR | Fair for time-sharing | Quantum choice matters |
| Priority | Flexible importance control | Starvation possible |

#### Deadlock Conditions

```text
1. Mutual exclusion
2. Hold and wait
3. No preemption
4. Circular wait
```

#### High-Yield Comparisons

| Concept A | Concept B | Difference |
|---|---|---|
| Process | Thread | Separate address space vs shared within process |
| Paging | Segmentation | Fixed-size blocks vs variable-size logical units |
| Mutex | Semaphore | Ownership-style lock vs signaling/counting primitive |
| User mode | Kernel mode | Restricted privilege vs full privileged access |

> Common trap: A thread is not an independent process. Threads share process resources but not all execution state.

#### Memory Tricks

- Deadlock needs all four conditions together
- RR uses time quantum
- LRU replaces least recently used page
- Thrashing means too much paging, too little useful execution

### Practice MCQs

#### MCQ 1

Which statement correctly distinguishes a process from a thread?

A. A thread always has its own separate address space  
B. A process cannot contain multiple threads  
C. Threads within the same process typically share address space  
D. Processes are always faster to create than threads

**Answer:** C  
**Explanation:** Threads of one process share memory and resources while keeping separate execution state.

#### MCQ 2

Which scheduling algorithm is most associated with time slicing?

A. FCFS  
B. Round Robin  
C. SJF  
D. Priority non-preemptive

**Answer:** B  
**Explanation:** Round Robin rotates processes using a fixed time quantum.

#### MCQ 3

Which of the following is not a necessary deadlock condition?

A. Mutual exclusion  
B. Circular wait  
C. Preemption  
D. Hold and wait

**Answer:** C  
**Explanation:** The required condition is no preemption, not preemption.

#### MCQ 4

A page fault occurs when:

A. The CPU cache is full  
B. Referenced page is not in main memory  
C. The page table has duplicate entries  
D. A process enters ready queue

**Answer:** B  
**Explanation:** The OS must bring the needed page from secondary storage into memory.

#### MCQ 5

Which page replacement algorithm can exhibit Belady’s anomaly?

A. FIFO  
B. LRU  
C. Optimal  
D. MRU only

**Answer:** A  
**Explanation:** FIFO can sometimes produce more page faults with more frames.

#### MCQ 6

Which synchronization problem is caused by unsafely shared data access?

A. Fragmentation  
B. Race condition  
C. Starvation  
D. Thrashing

**Answer:** B  
**Explanation:** Race conditions occur when outcome depends on interleaving of concurrent execution.

#### MCQ 7

Which memory allocation scheme uses fixed-size blocks?

A. Segmentation  
B. Paging  
C. Swapping only  
D. Overlaying

**Answer:** B  
**Explanation:** Paging divides logical memory into fixed-size pages and physical memory into frames.

#### MCQ 8

Which mode allows execution of privileged instructions?

A. User mode  
B. Kernel mode  
C. Thread mode only  
D. Scheduler mode only

**Answer:** B  
**Explanation:** Kernel mode has the necessary privilege to access protected operations.

#### MCQ 9

Which scheduling issue is most associated with priority scheduling without aging?

A. Deadlock  
B. Starvation  
C. Thrashing  
D. Internal fragmentation

**Answer:** B  
**Explanation:** Low-priority processes may wait indefinitely if high-priority tasks keep arriving.

#### MCQ 10

What is the main purpose of a semaphore in OS?

A. Store files permanently  
B. Encrypt kernel memory  
C. Coordinate concurrent access and signaling  
D. Replace CPU scheduling

**Answer:** C  
**Explanation:** Semaphores manage synchronization and resource access among processes or threads.

### Summary Sheet

- Rehearse process/thread differences, scheduling criteria, and synchronization primitives.
- Memorize deadlock conditions exactly.
- Be clear on paging vs segmentation and page-fault behavior.
- Expect MCQs on starvation, thrashing, RR quantum, and FIFO vs LRU.
