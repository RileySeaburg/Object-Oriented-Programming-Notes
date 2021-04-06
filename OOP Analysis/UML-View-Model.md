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
        - Examples include: 
            - ![Class diagram](https://youtu.be/UI6lqHOVHic)
            - ![State Transition diagram](https://youtu.be/OsmWASXE2IM)
            - ![Sequence diagram](https://youtu.be/pCK6prSq8aw)
            - ![Communication diagram](https://youtu.be/TL4ABTx_RtE)
            - Object diagram
    - Process view
        - Describes the process of the system and how the communicate with each other.
        - Helps the stakeholder to understand what needs to happen in the system.
    - Physical View
        - Models the execution environment of the system.
        - Models the software entities of the hardware that will host the entities.
        - Depicted through deployment diagrams.
    - Development View
        - Describes the modules or components of the system.
        - Helps manage the layers of the system.
        - Might include packages or libraries. 
        - Provides 2 diagrams for development view
            - Component Diagram
            - Package Diagram
    - Use Case View
        - All views a dependent on this view.
        - Illustrates the functionality of the system.
        - captures the goals of the user in the system
        - Can be created through diagrams or descriptions.