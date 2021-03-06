# Object Model Concepts

## Evolution of Languages

- Early computer languages were used for mathematical and scientific operations.
    - Freed the programmer from the intricacies of assembly languages.
- Growth in size and complexity led to evolution in languages to accommodate new features. 
    - e.g. automation for business applications.
- Slowly the languages evolved even more.
    - Software moved close to problem domain and further away from the machine. 

## Object Model

- The newer languages used classes & objects instead of subprograms and algorithms as building blocks.
- These languages build upon the object model.
- The object model is based on three important concepts.
    - Object oriented analysis
    - Object oriented design
    - Object oriented programming

### Object Oriented Analysis

*"OO analysis is a method of analysis that examines the requirements from the perspective of the classes and objects found in the vocabulary of the problem domain"*
                                        - Grady Booch
                                        ["Object Oriented Analysis & Design with Applications 3'rd Edition"](https://learning.oreilly.com/library/view/object-oriented-analysis-and/9780201895513/)
- This is the first step for develop an object oriented system.
- Investigation of the problem and requirements rather than the solution.
- Focuses on what the system is supposed to do rather than how it will be done. 
- Looks at the behavior of the system independent of it's domain.
- Examines the real-wold environment in which the system will operate. 
    - Includes people and things that will interact to produce some results
    - Analysed in basic abstract forms, in multiple iterations.
    - These abstractions later become classes in the problem domain.


#### Example OO Analysis *Library*

- Member requests a book from the library
- Librarian will search for the book in the library.
- If found, the book is issued.
    - The database is  updated with the issued book.
- If unavailable, the request is placed in a queue.
- If not found an order may be placed for the book.

#### Analysis

- Highest level analysis or abstraction
- This will continue until objects are uniquely identified.
- The objects are refined as abstractions with key characteristics.
- Emphasis on investigation rather than the solution.

### Object Oriented Design

*OO design is a method of design encompassing the process of OO decomposition and a notation for depicting both logical and physical as well as static and dynamic models of the system under design.* - Grady Booch ["Object Oriented Analysis & Design with Applications 3'rd Edition"](https://learning.oreilly.com/library/view/object-oriented-analysis-and/9780201895513/)

- Focuses on object oriented decomposition.
- Uses different notations to express different models of the system.
- High level concepts of analysis are mapped onto classes.
- Hierarchical associations among the classes are designed. 
- Results in a detailed description that specifies how the system is to be built using different technologies. 

![OOD Example Image](../public/OOD-Example-Image.png)

### Object Oriented Programming

*A method of implementation in which programs are organized as cooperative collections of objects, each of which represents an instance of some class, and whose callses are all members of a hierarchy of classes united via inheritance relationships.* - Grady Booch ["Object Oriented Analysis & Design with Applications 3'rd Edition"](https://learning.oreilly.com/library/view/object-oriented-analysis-and/9780201895513/)

- Uses objects as fundamental building blocks.
- Classes & objects are related through relationships. 
- Requires a programming language that supports:
    - Objects as abstractions
    - Classes
    - generalization of classes
- OOP Languages
    - Java
    - C++
    - C#
    - etc

## Summary

- Object model build upon three important concepts.
- Object oriented analysis, design and programming
- Analysis focuses on the problem.
- Design is about object oriented decomposition and expression of the design using notations.
- Programming is the implementation using an object oriented language.