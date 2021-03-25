# Decomposition

## Resolving complexity

- Human beings have a built in mechanism for dealing with with complexity/ 
- Decompose each part into smaller parts until each part makes sense individually.
- Integrate the parts to build the final system. 
- "divide et impera" - divide and rule
- Same principle is applied to programming languages. 


## Algorithmic Decomposition

- Decomposes the problem into Algorithms.
- Each algorithm is part of a series of steps (part of an overall process).
- Typically, a top-down approach is used.
    - Start with a big picture.
    - Break it down into smaller parts.
- These steps lead to the final result (like a flow chart)

### Disadvantages

- Development based on the high-level specification.
    - Often changes over time.
    - Parts have to be rewritten.
- Algorithms are very specific to the application, this, difficult to reuse.
- Difficult to add new features.
    - Algorithms are tightly wired to work together.
- Data is treated with low significance.
    - Data is shared between algorithms.
    - Unintentional modification can lead to disastrous results.
- Focus on operations
    - No idea about the entity on which the operation is performed.
    - Overall understanding of the application becomes complicated.
    - Does not map the real world problem

### Languages

- languages based on Algorithmic decomposition.
    - Fortran
    - Cobol
    - Pascal
    - C

#### Summary

- Algorithmic decomposition 
- Focus on operations rather than data
- Do not scale well
- Do not map to real life. 

## Object Oriented Decomposition

- Humans can abstract complexity and focus only on necessary details.
    - Unwanted details are ignored
    - deal with relevant details only
    - leads to simple entities in the problem domain

- Recognize relationship between these entities
    - Some entities may be generalized
- Understand how they interact and coordinate. 
- Coordination gives first to the functionality of the system.

- Uses Bottom-Up Design
- The system is decomposed as a set of autonomous, but cooperative agents
- These agents are objects and represent key abstractions in the problem domain.
    - Designed with detail
- Each object has its own behavior
- Models some object in the real world.
- The objects coordinate with each other. 
    - Coordination gives rise to the functionality of the system.
    - Send messages to each other through method calls.

### Advantages

- Follows separation of concerns.
    - Each entity has it's own responsibility. 
    - Addresses the complexity through organization.
- System is made of objects that represent real-life entities
- Maps closely to real-world problems
- Data has high importance
    - part of the object, not visible externally.
- Enables generalization of objects
    - Promotes reuse of common functionality.
    - Leads to smaller systems
- Evolve incrementally over a period of time. 