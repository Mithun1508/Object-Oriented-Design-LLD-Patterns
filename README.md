# Object-Oriented Language: The general expectation in the machine coding round (or) LLD round is that candidate writes Object Oriented Code. 
As the name suggests, Object-Oriented Languages revolve around everything about Objects. 

# Object-Oriented Principles: Knowing an Object-Oriented Language itself is not sufficient for writing extensible and maintainable code. 
Many Object-Oriented principles are designed to make the software extensible and maintainable. Some of the well-known principles are :

1)YAGNI: You Ain't Gonna Need It is a practice in software development that states that features should only be added when required and 
thus help trim away excess and inefficiency development to facilitate the desired increased frequency of releases)

2)DRY: Don't Repeat Yourself is a principle that states that don't repeat the code again and again. 
If there is a code that is duplicated then whenever a change needs to be made, the change has to be done in both places. So the developer has to remember all the places where the code is duplicated which are difficult and error-prone. Thus this principle states that the code should never be duplicated and has to refactor into its method or class and all other places need to use this method/class instead of duplicating the code.

3)SOLID: These are a set of 5 principles. Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion.
Apart from these, there are well-known principles such as favouring composition over inheritance, Encapsulating what varies, Striving for loosely coupled classes, etc.

# UML Diagrams: 
     UML is an acronym that stands for Unified Modeling Language and is a standard for modelling, visualizing, and documenting the artefacts of software systems. It is not a programming language but a tool to visually depict different types of diagrams that can be useful for building the software.
There are 14 different types of UML Diagrams and these 14 diagrams are classified into 2 high-level groups.
 1) Structural Diagrams: They represent the static view of the system. Class Diagram, Composite Structure Diagram, Object Diagram, Component Diagram, Deployment Diagram, Profile Diagram, and Package Diagram are part of Structural Diagrams.
 
 2) Behavioural Diagrams: They represent the dynamic view of the system. Activity Diagram, State Machine Diagram, Use Case Diagram, Interaction Overview Diagram, Timing Diagram, Sequence Diagram, and Communication Diagram are part of Behavioral Diagrams.

Class Diagram & Use Case Diagram are generally used

Solving an LLD problem can be divided into mainly 2 stages:


1. Class Diagram & Use Case Diagram & Schema Diagram (If required): Once the requirements are gathered, define the core classes and objects, how the different classes interact with each other, and actors who interact with the system, the use cases for each actor, etc. Draw the class diagram and use a case diagram (can be optional, ask the interviewer) for the system. Define the relations between classes by observing the interactions between them. If Class Diagram & Use Case Diagram helps in representing the requirements of systems and the relationship between different classes, a Schema Diagram (also called an ER Diagram) helps in how the data models look and how to store the data in the database. Interviewers may not ask to write the code to store the data in the actual database but they may be interested in how the model looks like and the relationship between them. It is easy to create the Schema Diagram from the Class Diagram. Each class in the class diagram becomes a table in Schema Diagram and the relationship between classes becomes the multiplicity between tables.

2. Working Clean Code: Finally once the thoughts are structured using Class Diagram, Use Case Diagram, and Schema Diagram (if required), the Candidate can start writing the code. Apply the Design Patterns, Object-Oriented Principles & SOLID Principles wherever is possible to make the system reusable, extensible, and maintainable. Make sure the code is well structured and follow the clean coding practices to make the classes and method clean. Don't try to fit design patterns to code but check if a given problem can be solved using any available design pattern. Take care of the readability of code while taking care of all of the above. Yes, software engineering is hard.
