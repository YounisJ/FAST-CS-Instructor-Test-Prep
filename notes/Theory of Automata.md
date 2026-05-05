
## Theory of Automata

### High-Yield Topics

- DFA, NFA, epsilon-NFA definitions and behavior
- Regular expressions and regular languages
- Conversions: regex to automata, NFA to DFA
- DFA minimization and equivalence intuition
- CFG basics, derivations, parse trees, ambiguity
- PDA and context-free languages
- Turing machines, decidable vs recognizable intuition
- Chomsky hierarchy basics
- Pumping lemma for regular languages
- Language classification: regular vs CFL vs non-CFL

### Revision Notes

#### Core Definitions

| Model | Memory | Recognizes |
|---|---|---|
| DFA | Finite control only | Regular languages |
| NFA | Finite control with nondeterminism | Regular languages |
| PDA | Finite control + stack | Context-free languages |
| TM | Tape (unbounded model) | Recursively enumerable languages |

#### Formal Objects Quick View

```text
DFA = (Q, Sigma, delta, q0, F)
CFG = (V, Sigma, P, S)
```

#### Key Equivalences

| Form | Equivalent Power |
|---|---|
| DFA | Regular languages |
| NFA | Regular languages |
| Regular expression | Regular languages |
| Right-linear grammar | Regular languages |

> Common trap: NFA is not more powerful than DFA. It is often more compact, but both recognize exactly the same class of languages.

#### Classic Language Classification

| Language | Regular? | Context-Free? |
|---|---|---|
| `a* b*` | Yes | Yes |
| `{ a^n b^n | n >= 0 }` | No | Yes |
| `{ a^n b^n c^n | n >= 0 }` | No | No |
| Even number of `1`s | Yes | Yes |
| Palindromes over `{a,b}` | No | Yes |

#### Conversion Intuition

- Regex can be converted to epsilon-NFA, then to NFA/DFA.
- NFA to DFA uses subset construction.
- DFA minimization merges equivalent indistinguishable states.
- PDA naturally handles nested/counting patterns using a stack.

#### Pumping Lemma Quick Sheet

```text
If L is regular, then there exists p such that every string s in L with |s| >= p
can be written as s = xyz where:
1. |xy| <= p
2. |y| >= 1
3. For all i >= 0, x y^i z is in L
```

> Common trap: Pumping lemma is generally used to disprove regularity, not to prove that a language is regular.

#### Memory Tricks

- DFA = one path per symbol from each state
- NFA = may branch
- PDA = stack helps count/match structure
- TM = most powerful standard model in this course scope
- `a^n b^n` needs memory, so not regular

### Automata Practice MCQs

#### MCQ 1

Which pair has equal expressive power?

A. DFA and PDA  
B. DFA and NFA  
C. PDA and TM  
D. CFG and TM

**Answer:** B  
**Explanation:** DFA and NFA both recognize exactly the regular languages.

#### MCQ 2

Which language is regular?

A. `{ a^n b^n | n >= 0 }`  
B. `{ w in {0,1}* | w has even number of 1s }`  
C. `{ a^n b^n c^n | n >= 0 }`  
D. Set of palindromes over `{a,b}`

**Answer:** B  
**Explanation:** A finite automaton can track parity of `1`s using finite states.

#### MCQ 3

Which machine is the natural recognizer for context-free languages?

A. DFA  
B. NFA  
C. PDA  
D. Finite-state transducer only

**Answer:** C  
**Explanation:** PDA adds a stack, which is enough for CFL structure like matching counts in nested ways.

#### MCQ 4

The primary purpose of the pumping lemma for regular languages is to:

A. Build a DFA from regex  
B. Minimize NFA  
C. Show that some languages are not regular  
D. Convert CFG to PDA

**Answer:** C  
**Explanation:** It is usually used by contradiction to prove non-regularity.

#### MCQ 5

In subset construction, each DFA state corresponds to:

A. One NFA transition  
B. One input symbol  
C. A set of NFA states  
D. A stack content snapshot

**Answer:** C  
**Explanation:** The constructed DFA simulates all possible NFA states at once.

#### MCQ 6

Which of the following is not context-free?

A. `{ a^n b^n | n >= 0 }`  
B. Balanced parentheses  
C. `{ a^n b^n c^n | n >= 0 }`  
D. Simple arithmetic expressions with parentheses

**Answer:** C  
**Explanation:** Equal matching across three independent symbol groups is beyond CFL power.

#### MCQ 7

A DFA differs from an NFA because in a DFA:

A. States may have multiple transitions on same symbol  
B. There is exactly one transition for each state-symbol pair  
C. Epsilon moves are mandatory  
D. Final states are not allowed

**Answer:** B  
**Explanation:** Determinism requires one defined next move per state and input symbol.

#### MCQ 8

Which statement about regular expressions is correct?

A. They can describe exactly all context-free languages  
B. They are weaker than DFA  
C. They describe exactly regular languages  
D. They require a stack for evaluation power

**Answer:** C  
**Explanation:** Regular expressions characterize the regular languages.

#### MCQ 9

Which language class is recognized by Turing machines in the basic theory sense?

A. Only finite languages  
B. Only regular languages  
C. Recursively enumerable languages  
D. Only context-free languages

**Answer:** C  
**Explanation:** Turing machines recognize recursively enumerable languages.

#### MCQ 10

Which statement is true about DFA minimization?

A. It always increases number of states  
B. It merges distinguishable states  
C. It removes unreachable and equivalent states  
D. It changes the recognized language

**Answer:** C  
**Explanation:** Minimization preserves the language while reducing redundant structure.

### Additional Automata MCQs

#### MCQ 11

If a language is recognized by an NFA, then:

A. It may not be recognized by any DFA  
B. It is always context-sensitive only  
C. There exists an equivalent DFA for it  
D. It must be infinite

**Answer:** C  
**Explanation:** NFA and DFA are equivalent in expressive power.

#### MCQ 12

Which of the following is most suitable for proving that `{ a^n b^n | n >= 0 }` is not regular?

A. BFS  
B. Pumping lemma  
C. Dijkstra’s algorithm  
D. SQL normalization

**Answer:** B  
**Explanation:** Pumping lemma is the standard tool for this non-regularity proof.

#### MCQ 13

Ambiguity in a CFG means:

A. Some terminal has two ASCII codes  
B. A string has more than one parse tree or leftmost derivation  
C. Grammar has epsilon production  
D. Grammar is regular

**Answer:** B  
**Explanation:** Ambiguity is about multiple valid structural derivations for the same string.

#### MCQ 14

Balanced parentheses language is naturally modeled by:

A. DFA  
B. PDA  
C. Hash table  
D. Finite grammar only

**Answer:** B  
**Explanation:** A stack is ideal for matching nested open and close symbols.

#### MCQ 15

Which of the following is always regular?

A. Finite language  
B. `{ a^n b^n | n >= 0 }`  
C. All palindromes  
D. `{ ww | w in {0,1}* }`

**Answer:** A  
**Explanation:** Every finite language is regular because it can be enumerated by a finite automaton or regex.

### Summary Sheet

- Master the equivalence of DFA, NFA, regex, and regular grammar.
- Memorize classic language classifications.
- Practice pumping lemma structure carefully.
- Expect conceptual traps around determinism, equivalence, ambiguity, and machine power.
