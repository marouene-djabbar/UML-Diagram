# Senario

You are tasked with developing a use case diagram for a university registration system. The system allows students to register for courses online, view their course schedules, and make payments. Faculty members can view student rosters for their courses and submit grades. The administration can generate reports on student enrollment and course offerings. Develop a use case diagram capturing the essential functionalities of this system. Ignore any login procedures.

Additional Information:
-Students can add or drop courses from their schedules.
-Students can view their grades and academic history.
-Faculty members can view and update course-related information.
-Faculty members can submit grades for students enrolled in their courses.
-Administrators can access reports on student enrollment, course offerings, and payment statuses.

# Potential solution

![image](https://github.com/marouene-djabbar/UML-Diagram/assets/165311266/b94905dd-cadf-4e4a-b480-5df8cfc800f9)

# Use Case Diagram

## What is a Use Case Diagram?

A Use Case Diagram is a type of diagram used in software and systems engineering to describe the behavior of a system from a user's standpoint. It helps define the system's interactions with external entities (actors), focusing on the functionality and goals the system achieves through these interactions.

## Components of a Use Case Diagram:

### Actors: These represent roles that interact with the system. Actors can be human users, other systems, or external hardware. They are not part of the system but interact with it.
### Use Cases: These are the specific actions or processes that the system performs in response to actor interactions. Each use case represents a distinct goal that the system helps an actor achieve.
### Associations: Lines connecting actors to use cases, indicating who can initiate or participate in each use case.
### System Boundary: Often depicted as a box, the boundary encloses all use cases, defining what is considered as part of the system and what is outside.

## Key Relationships in Use Case Diagrams:

### Include Relationship: This is used when a use case is inherently included within another use case, often indicating that the included use case is a necessary part of the execution of the including use case.
### Extend Relationship: This describes situations where a use case conditionally adds behaviors or steps to another use case, depending on certain conditions or choices made during runtime.
### Generalization Relationship: This is used when an actor inherits the role of another actor, showing a hierarchical relationship between actors.




