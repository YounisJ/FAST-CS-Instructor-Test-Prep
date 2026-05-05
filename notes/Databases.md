
## Databases

### High-Yield Topics

- Relational model, tuples, attributes, domains
- Keys: super key, candidate key, primary key, foreign key
- Functional dependencies and normalization
- SQL basics and conceptual queries
- Joins: inner, outer, natural, self join
- Transactions, ACID, concurrency, serializability
- Indexing: clustered vs non-clustered, B+ tree basics

### Revision Notes

#### Core Definitions

| Term | Meaning |
|---|---|
| Super key | Any attribute set that uniquely identifies a tuple |
| Candidate key | Minimal super key |
| Primary key | Chosen candidate key |
| Foreign key | Attribute referencing key in another table |
| Functional dependency | If X matches, Y must match |
| Transaction | Logical unit of database work |

#### Normal Forms Quick Table

| Normal Form | Removes | High-Yield Angle |
|---|---|---|
| 1NF | Repeating groups / non-atomic values | Atomic attributes |
| 2NF | Partial dependency | Composite key issue |
| 3NF | Transitive dependency | Non-key depends on non-key |
| BCNF | Stronger FD violations | Every determinant should be a candidate key |

#### ACID

```text
A = Atomicity
C = Consistency
I = Isolation
D = Durability
```

#### High-Yield Comparisons

| Concept A | Concept B | Difference |
|---|---|---|
| Primary key | Foreign key | Uniquely identifies vs references another relation |
| Clustered index | Non-clustered index | Affects physical order vs separate access path |
| Inner join | Outer join | Matching rows only vs preserving unmatched side |
| 3NF | BCNF | BCNF is stricter |

> Common trap: A foreign key does not need to be unique, but a primary key does.

#### Memory Tricks

- Candidate key = minimal unique
- 2NF fixes part-key dependence
- 3NF fixes non-key to non-key dependence
- BCNF is stricter than 3NF

### Practice MCQs

#### MCQ 1

Which key must uniquely identify every tuple in a relation and is chosen among candidate keys?

A. Foreign key  
B. Composite attribute  
C. Primary key  
D. Secondary index

**Answer:** C  
**Explanation:** A primary key is a selected candidate key used for unique identification.

#### MCQ 2

A relation is in 2NF if it is already in 1NF and has no:

A. Transitive dependencies  
B. Partial dependencies on a candidate key  
C. Foreign keys  
D. Super keys

**Answer:** B  
**Explanation:** 2NF removes partial dependency, especially relevant with composite keys.

#### MCQ 3

Which ACID property ensures committed data survives system failure?

A. Atomicity  
B. Isolation  
C. Durability  
D. Consistency

**Answer:** C  
**Explanation:** Durability guarantees persistence after commit.

#### MCQ 4

Which SQL clause is used to filter groups after aggregation?

A. WHERE  
B. ORDER BY  
C. HAVING  
D. DISTINCT

**Answer:** C  
**Explanation:** `HAVING` applies conditions on grouped results.

#### MCQ 5

A foreign key is primarily used to enforce:

A. Domain compression  
B. Referential integrity  
C. Query optimization  
D. Backup scheduling

**Answer:** B  
**Explanation:** It ensures references correspond to existing parent keys.

#### MCQ 6

Which normal form specifically targets transitive dependency removal?

A. 1NF  
B. 2NF  
C. 3NF  
D. 4NF

**Answer:** C  
**Explanation:** 3NF removes dependencies where non-key depends on another non-key.

#### MCQ 7

Which index structure is classically associated with database indexing and efficient range queries?

A. Stack  
B. B+ tree  
C. AVL only  
D. Circular queue

**Answer:** B  
**Explanation:** B+ trees support efficient search and range traversal.

#### MCQ 8

Dirty read means:

A. Reading uncommitted data from another transaction  
B. Reading the same row twice  
C. Losing a committed update permanently  
D. Reading a damaged disk page

**Answer:** A  
**Explanation:** Dirty reads occur when one transaction reads data not yet committed by another.

#### MCQ 9

Which join returns only matching rows from both tables?

A. Left outer join  
B. Right outer join  
C. Full outer join  
D. Inner join

**Answer:** D  
**Explanation:** Inner join includes only rows satisfying the join condition in both relations.

#### MCQ 10

BCNF is stricter than 3NF because:

A. It removes all foreign keys  
B. It requires every determinant to be a candidate key  
C. It forbids composite keys  
D. It allows more redundancy

**Answer:** B  
**Explanation:** BCNF strengthens the dependency condition beyond 3NF.

### Summary Sheet

- Master keys, dependencies, normal forms, ACID, joins, and indexing.
- Expect conceptual SQL and transaction anomalies in MCQs.
- Differentiate 2NF, 3NF, and BCNF cleanly.
- Revise dirty read, non-repeatable read, lost update, and serializability at a high level.
