
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
