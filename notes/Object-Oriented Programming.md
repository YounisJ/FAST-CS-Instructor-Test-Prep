

## Object-Oriented Programming

### High-Yield Topics

- Encapsulation, abstraction, inheritance, polymorphism
- Constructors, destructors, copy behavior
- Overloading vs overriding
- Static binding vs dynamic binding
- Access specifiers and visibility
- Abstract classes, interfaces, virtual functions
- Composition vs inheritance

### Revision Notes

#### OOP Pillars

| Principle | Meaning | Typical MCQ Angle |
|---|---|---|
| Encapsulation | Bundle data and methods together | Access control, data hiding |
| Abstraction | Expose essential behavior, hide details | Interfaces, abstract classes |
| Inheritance | Derive new class from existing one | Reuse, IS-A relationship |
| Polymorphism | Same interface, different behavior | Overriding, dynamic dispatch |

#### Key Comparisons

| Concept A | Concept B | Difference |
|---|---|---|
| Overloading | Overriding | Same name with different parameters vs same signature in subclass |
| Compile-time binding | Run-time binding | Decided by compiler vs decided during execution |
| Inheritance | Composition | IS-A vs HAS-A |
| Abstract class | Interface | Shared partial implementation vs pure contract (language dependent) |

> Common trap: Overloading is not the same as overriding. MCQs often disguise this by changing only parameter types.

#### Constructor/Destructor Notes

- Constructor initializes object state.
- Destructor performs cleanup.
- If deleting a derived object through a base pointer, a virtual destructor is usually required in C++.

#### Memory Tricks

- Overload: “same name, new input list”
- Override: “child replaces parent behavior”
- Composition: “has-a”
- Inheritance: “is-a”

### Practice MCQs

#### MCQ 1

Which OOP principle is most closely related to data hiding?

A. Inheritance  
B. Encapsulation  
C. Polymorphism  
D. Delegation

**Answer:** B  
**Explanation:** Encapsulation hides internal data behind controlled access methods.

#### MCQ 2

Method overriding is associated with:

A. Compile-time polymorphism  
B. Run-time polymorphism  
C. Static memory allocation  
D. Function templates only

**Answer:** B  
**Explanation:** Overriding allows dynamic dispatch based on actual object type.

#### MCQ 3

Which relationship is best modeled by inheritance?

A. Car has Engine  
B. Library has Books  
C. Dog is Animal  
D. Computer has CPU

**Answer:** C  
**Explanation:** Inheritance represents an IS-A relationship.

#### MCQ 4

Which of the following is true about function overloading?

A. It requires inheritance  
B. It uses the same name with different parameter lists  
C. It is always resolved at runtime  
D. It requires virtual functions

**Answer:** B  
**Explanation:** Overloading is resolved by compiler based on signature.

#### MCQ 5

A class with at least one pure virtual method is typically:

A. Final class  
B. Concrete class  
C. Abstract class  
D. Friend class

**Answer:** C  
**Explanation:** Abstract classes cannot usually be instantiated directly.

#### MCQ 6

What is the main benefit of composition over deep inheritance in many designs?

A. It guarantees faster execution  
B. It often provides more flexible coupling of behavior  
C. It removes all memory overhead  
D. It avoids object creation

**Answer:** B  
**Explanation:** Composition allows assembling behavior with less rigid hierarchy dependence.

#### MCQ 7

Which keyword/concept enables late binding in C++-style OOP?

A. Static  
B. Friend  
C. Virtual  
D. Inline

**Answer:** C  
**Explanation:** Virtual functions enable dynamic dispatch.

#### MCQ 8

If a derived class object is assigned to a base class object by value, what issue can occur?

A. Deadlock  
B. Slicing  
C. Paging  
D. Serialization

**Answer:** B  
**Explanation:** Only the base-class portion may be copied, losing derived-specific state.

### Summary Sheet

- Overloading is compile-time; overriding is runtime.
- Use inheritance for IS-A, composition for HAS-A.
- Abstract class questions often test instantiation rules and polymorphism.
- Watch for slicing, destructor behavior, and access modifier traps.
