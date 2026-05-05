
## Artificial Intelligence

### High-Yield Topics

- Problem formulation and state-space search
- Uninformed search: BFS, DFS, Uniform Cost Search
- Informed search: Greedy Best-First, A*
- Heuristics: admissible, consistent
- Knowledge representation: propositional logic, FOL basics
- Reasoning: forward chaining, backward chaining (basic idea)
- Learning types: supervised, unsupervised, reinforcement
- Basic agents: reflex, goal-based, utility-based

### Revision Notes

#### Core Definitions

| Term | Meaning |
|---|---|
| State space | All possible states reachable in a problem |
| Heuristic | Estimate of distance/cost to goal |
| Admissible heuristic | Never overestimates true goal cost |
| Consistent heuristic | Obeys triangle inequality style condition |
| Agent | Entity that perceives and acts |
| Utility-based agent | Chooses action maximizing expected utility |

#### Search Comparison

| Algorithm | Uses Heuristic? | Complete? | Optimal? |
|---|---|---|---|
| BFS | No | Yes (finite branching) | Yes for equal step cost |
| DFS | No | Not always | No |
| Uniform Cost Search | No | Yes | Yes |
| Greedy Best-First | Yes | Not always ideal | No |
| A* | Yes | Yes under standard conditions | Yes with admissible heuristic |

#### High-Yield Comparisons

| Concept A | Concept B | Difference |
|---|---|---|
| BFS | DFS | Shallowest expansion vs depth preference |
| Greedy | A* | Uses h only vs g + h |
| Supervised | Unsupervised | Labeled vs unlabeled data |
| Goal-based | Utility-based | Goal satisfaction vs preference optimization |

> Common trap: An admissible heuristic is about not overestimating, not about always being accurate.

#### Memory Tricks

- BFS finds shallowest first
- Greedy uses only guess to goal
- A* = cost so far + guess left
- Supervised means labeled examples

### Practice MCQs

#### MCQ 1

Which search algorithm evaluates nodes using `f(n) = g(n) + h(n)`?

A. BFS  
B. DFS  
C. A*  
D. Greedy Best-First

**Answer:** C  
**Explanation:** A* combines exact cost so far with heuristic estimate to goal.

#### MCQ 2

An admissible heuristic is one that:

A. Is always zero  
B. Never overestimates the actual remaining cost  
C. Always equals the true cost  
D. Is larger than the true cost

**Answer:** B  
**Explanation:** Admissibility means optimistic estimation.

#### MCQ 3

Which learning paradigm uses labeled input-output pairs?

A. Reinforcement learning  
B. Unsupervised learning  
C. Supervised learning  
D. Evolutionary search only

**Answer:** C  
**Explanation:** Supervised learning relies on labeled training examples.

#### MCQ 4

Which search strategy is guaranteed optimal when all step costs are equal?

A. BFS  
B. DFS  
C. Greedy Best-First  
D. Hill climbing

**Answer:** A  
**Explanation:** BFS returns the shallowest goal, which is optimal for unit-cost edges.

#### MCQ 5

A utility-based agent differs from a purely goal-based agent because it:

A. Cannot search  
B. Considers preference among goal states  
C. Uses no environment model  
D. Ignores uncertainty

**Answer:** B  
**Explanation:** Utility allows comparing multiple goal-achieving outcomes.

#### MCQ 6

Which algorithm may get trapped by local optima because it focuses on apparently best immediate choice?

A. Greedy search  
B. BFS  
C. Uniform Cost Search  
D. Iterative deepening only

**Answer:** A  
**Explanation:** Greedy methods may prefer locally attractive states that block global optimum.

#### MCQ 7

Forward chaining is most naturally described as:

A. Starting from query and working backward to premises  
B. Starting from facts and applying rules toward conclusions  
C. Randomly selecting clauses  
D. Sorting predicates alphabetically

**Answer:** B  
**Explanation:** Forward chaining derives consequences from known facts.

#### MCQ 8

Which of the following is not an uninformed search strategy?

A. BFS  
B. DFS  
C. Uniform Cost Search  
D. Greedy Best-First Search

**Answer:** D  
**Explanation:** Greedy Best-First uses a heuristic.

### Summary Sheet

- Memorize search algorithm properties and heuristic conditions.
- Distinguish greedy from A* precisely.
- Revise agent types and learning categories at definition level.
- Expect MCQs built around completeness, optimality, and misconceptions about heuristics.
