
## Discrete Structures

### High-Yield Topics

- Propositional logic, predicate logic, truth tables, inference rules
- Sets, power sets, Cartesian products
- Relations: reflexive, symmetric, transitive, antisymmetric, equivalence
- Functions: injective, surjective, bijective
- Counting: permutations, combinations, pigeonhole principle
- Proof techniques: direct, contradiction, contrapositive, induction
- Graph theory: trees, connectivity, degree, bipartite graphs
- Basic number theory: divisibility, primes, modular arithmetic

### Revision Notes

#### Core Definitions

| Term | Meaning |
|---|---|
| Proposition | Statement that is true or false |
| Tautology | Always true formula |
| Contradiction | Always false formula |
| Equivalence relation | Reflexive, symmetric, transitive relation |
| Bijection | Function that is both one-to-one and onto |
| Tree | Connected acyclic graph |

#### Key Formula Sheet

```text
Subsets of an n-element set = 2^n
Permutations: P(n, r) = n! / (n-r)!
Combinations: C(n, r) = n! / (r!(n-r)!)
```

#### High-Yield Comparisons

| Concept A | Concept B | Difference |
|---|---|---|
| Permutation | Combination | Order matters vs order does not matter |
| Symmetric | Antisymmetric | aRb implies bRa vs both imply a=b |
| Injective | Surjective | Unique outputs mapping vs all codomain covered |
| Tree | General graph | Connected and acyclic vs no such guarantee |

> Common trap: Symmetric and antisymmetric are not opposites. A relation can be neither, either, or both under certain conditions.

#### Memory Tricks

- Permutation = position matters
- Combination = committee, order irrelevant
- Tree = connected + no cycle
- Equivalence relation = RST: reflexive, symmetric, transitive

### Practice MCQs

#### MCQ 1

A relation is an equivalence relation if it is:

A. Reflexive and antisymmetric only  
B. Symmetric and transitive only  
C. Reflexive, symmetric, and transitive  
D. Antisymmetric and transitive only

**Answer:** C  
**Explanation:** Those three properties exactly define equivalence relation.

#### MCQ 2

How many subsets does a set with 6 elements have?

A. 12  
B. 36  
C. 64  
D. 720

**Answer:** C  
**Explanation:** Number of subsets is `2^n`, so `2^6 = 64`.

#### MCQ 3

Which proof method is most natural for statements of the form “for all n >= 1” involving natural numbers?

A. Proof by induction  
B. Proof by random testing  
C. Proof by table lookup  
D. Proof by contradiction only

**Answer:** A  
**Explanation:** Induction is designed for propositions indexed by integers.

#### MCQ 4

In a simple undirected graph, the sum of degrees of all vertices equals:

A. Number of vertices  
B. Number of edges  
C. Twice the number of edges  
D. Square of the number of vertices

**Answer:** C  
**Explanation:** Each edge contributes 2 to the total degree count.

#### MCQ 5

Which function type guarantees every element of the codomain has a preimage?

A. Injective  
B. Surjective  
C. Partial  
D. Identity only

**Answer:** B  
**Explanation:** Surjective means onto; every codomain element is hit.

#### MCQ 6

A connected acyclic graph with `n` vertices has how many edges?

A. `n`  
B. `n+1`  
C. `n-1`  
D. `2n`

**Answer:** C  
**Explanation:** This is a defining property of trees.

#### MCQ 7

Which statement about combinations is correct?

A. Order matters  
B. Repetition is always forbidden by definition  
C. They count selections where order does not matter  
D. They always exceed permutations

**Answer:** C  
**Explanation:** Combination counts selection without arranging order.

#### MCQ 8

If a function is both injective and surjective, it is:

A. Partial  
B. Bijective  
C. Symmetric  
D. Equivalent

**Answer:** B  
**Explanation:** A bijection is one-to-one and onto.

### Summary Sheet

- Master relations, functions, counting, graphs, and induction.
- Watch property wording carefully in relation MCQs.
- Rehearse subsets, permutations, combinations, tree properties, and degree sum rule.
