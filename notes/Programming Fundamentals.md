
## Programming Fundamentals

### High-Yield Topics

- Data types, literals, variables, scope, lifetime
- Operators, precedence, associativity, short-circuit behavior
- Control structures: `if`, `switch`, loops, nested loops
- Functions: parameters, return types, recursion, stack behavior
- Arrays, strings, pointers/references, memory basics
- Common runtime issues: overflow, off-by-one, uninitialized variables

### Revision Notes

#### Core Definitions

| Term | Meaning |
|---|---|
| Variable scope | Region where a variable is accessible |
| Lifetime | Duration for which a variable exists in memory |
| Pass by value | Copy passed to function |
| Pass by reference | Original object/location is indirectly modified |
| Recursion | Function calling itself on smaller subproblems |

#### Operator Priority Reminders

```text
Highest (common): (), unary, *, /, %, +, -, relational, equality, &&, ||, assignment
```

> Common trap: `a < b < c` is not a mathematical chain in C/C++-style languages. It is evaluated left to right using boolean/integer conversion.

#### High-Yield Comparisons

| Concept A | Concept B | Key Difference |
|---|---|---|
| `while` | `do-while` | `do-while` executes at least once |
| Local variable | Global variable | Local has limited scope; global wider visibility |
| Array | Linked structure | Array has contiguous memory; linked structure does not |
| Value parameter | Reference parameter | Copy vs original effect |

#### Memory Tricks

- Off-by-one: think `0` to `n-1`, not `1` to `n`
- `&&` stops on false, `||` stops on true
- Recursion always needs a base case

### Practice MCQs

#### MCQ 1

Which loop is guaranteed to execute its body at least once?

A. `for`  
B. `while`  
C. `do-while`  
D. Infinite loop only

**Answer:** C  
**Explanation:** `do-while` checks the condition after one execution.

#### MCQ 2

If `int x = 5 / 2;`, the value of `x` in most statically typed languages like C/C++/Java is:

A. 2.5  
B. 3  
C. 2  
D. Undefined

**Answer:** C  
**Explanation:** Integer division truncates the fractional part.

#### MCQ 3

What is the main risk in a recursive function without a proper base case?

A. Compilation error  
B. Syntax error  
C. Stack overflow  
D. Heap corruption

**Answer:** C  
**Explanation:** Recursive calls continue until stack space is exhausted.

#### MCQ 4

Which statement about short-circuit evaluation is correct?

A. Both operands are always evaluated in `&&` and `||`  
B. `A && B` does not evaluate `B` if `A` is false  
C. `A || B` never evaluates `B`  
D. Short-circuit applies only to arithmetic operators

**Answer:** B  
**Explanation:** For `&&`, once false is known, the result is fixed.

#### MCQ 5

Given an array of size `n`, the last valid index is usually:

A. `n`  
B. `n+1`  
C. `n-1`  
D. Depends only on compiler

**Answer:** C  
**Explanation:** Standard zero-based indexing runs from `0` to `n-1`.

#### MCQ 6

Which statement best describes pass by value?

A. The original variable is always modified  
B. A copy of the argument is passed  
C. Only pointers can be passed  
D. It is slower than pass by reference in every case

**Answer:** B  
**Explanation:** Pass by value sends a copy, so the caller’s original remains unchanged.

#### MCQ 7

Which error is most strongly associated with loop boundaries?

A. Deadlock  
B. Off-by-one error  
C. Race condition  
D. Fragmentation

**Answer:** B  
**Explanation:** Incorrect start/end conditions often skip or overrun one element.

#### MCQ 8

An uninitialized local variable in languages like C/C++ generally contains:

A. Zero always  
B. Null always  
C. Garbage/indeterminate value  
D. Compiler-generated default average value

**Answer:** C  
**Explanation:** Local primitive variables are not automatically initialized in C/C++.

### Summary Sheet

- Prioritize operator precedence, loop behavior, recursion, arrays, and parameter passing.
- Watch for integer division, boundary conditions, and side effects.
- In MCQs, test options by mentally simulating execution line by line.
