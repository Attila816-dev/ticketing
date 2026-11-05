# UML and Diagram Questions

1. What diagram types do you have on your current project?

   For a ticketing project, the most relevant diagram types are:
   - Use case diagram: shows actors and system functions such as creating a ticket, assigning an agent, and resolving a ticket.
   - Class diagram: shows entities like User, Ticket, Agent, Comment, and their relationships.
   - Sequence diagram: shows how objects interact during a process, such as creating a ticket or resolving an issue.
   - ER diagram: shows the database structure and relationships between tables like users, tickets, and comments.
   - Activity diagram: shows workflow and decision paths, such as ticket handling from open to closed.
   - State diagram: shows the lifecycle of a ticket, for example Open → In Progress → Resolved → Closed.

2. What are the pros and cons of UML diagrams?

   Pros:
   - Standardized notation used in software engineering.
   - Improves communication between developers, testers, and non-technical stakeholders.
   - Helps document the system clearly before or during implementation.
   - Makes complex systems easier to understand.
   - Helps identify design issues early.

   Cons:
   - Can become too detailed and time-consuming to maintain.
   - Some diagrams are difficult to read if not designed clearly.
   - UML may not cover every project-specific requirement fully.
   - Stakeholders without UML knowledge may struggle to interpret them.
   - Large diagrams can become confusing if overused.

3. What is the difference between a structural diagram and a behavioral diagram in UML?

   Structural diagrams describe the static aspects of the system, meaning what the system is made of.
   - Examples: class diagram, component diagram, deployment diagram.
   - They show the entities and their relationships.

   Behavioral diagrams describe the dynamic aspects of the system, meaning how the system behaves and interacts over time.
   - Examples: use case diagram, sequence diagram, activity diagram, state diagram.
   - They show how actions and interactions happen.

   In short: structural diagrams focus on "what" the system contains, while behavioral diagrams focus on "how" the system works.

4. Name the relationship types in a use case diagram

   The main relationship types in a use case diagram are:
   - Association: connects an actor to a use case.
   - Include: one use case always includes another use case's behavior.
   - Extend: one use case adds optional behavior to another use case.
   - Generalization: one actor or use case is a specialized version of another.

   Example in a ticketing system:
   - User associates with "Create Ticket"
   - "Create Ticket" includes "Validate Input"
   - "Submit Ticket" may extend with "Attach File"
   - Admin may generalize from User

5. What is the sequence diagram?

   A sequence diagram is a UML behavioral diagram that shows how objects or components interact with each other in a specific process, in the order they occur.

   It usually includes:
   - Actors or objects
   - Lifelines
   - Messages between lifelines
   - Time order from top to bottom

   Example in a ticketing system:
   - User sends a ticket request.
   - System validates the input.
   - Database stores the ticket.
   - Ticket is assigned to an agent.
   - Agent receives notification.

   Sequence diagrams are useful for understanding the flow of communication and the order of operations in a system.