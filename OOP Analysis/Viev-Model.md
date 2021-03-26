# View Model

- Defines a coherent set of views that are used in construction of a software architecture.
- A view represents the whole system from the perspective of a related set of concerns.
- This allows different stakeholders to view the system from their viewpoint or perspective.
- The view model is an effective approach for dealing with the inherent complexity of the large distributed systems

## Intent

- The intent is to use a mechanism that separates the different aspects of the software system into different views.
- Different stakeholders have different interests in the systems.
    - Programmers - classes
    - Administrators - hardware, network configuration, etc.
    - Customers - usability

## View of the Model

- UML Model diagrams can be broken into different perspectives or views.
- Can be explains through Kruchten's 4+1 model
    - Logical view
        - Shows the parts that make up the systems and how they interact which each other.
        - Represents the abstractions that are use in the problem domain.
        - Abstractions are classes or objects.
        - Ex. 
            - Class diagram 
            - State diagram
            - Sequence diagram
            - Communication diagram
            - Object diagram
    - Process view
        - Describes the process of the system and how the communicate with each other.
