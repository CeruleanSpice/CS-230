# CS-230
Draw It or Lose it Software Design Document
---

Here's the revised README file that incorporates information from your software design document:  

---

# The Gaming Room Software Design Document  

This repository contains the completed software design document for The Gaming Room, detailing the software architecture and design for their game, *Draw It or Lose It*. Below is a summary of the project and reflections on the design process.  

## Project Summary  

**Who was the client?**  
The Gaming Room, a company seeking to expand its Android-based game, *Draw It or Lose It*, into a web-based, multi-platform application.  

**What were their requirements?**  
The client’s main requirements included:  
- Supporting multiple teams with unique names for teams and games.  
- Enforcing a single-instance memory model for managing the game state.  
- Achieving platform independence for desktop (Windows, macOS, Linux) and mobile (iOS, Android).  
- Scalability, maintainability, and secure handling of data.  

## Reflections on the Process  

**What did I do particularly well?**  
I excelled in designing a scalable system architecture that adheres to object-oriented programming principles like inheritance, encapsulation, and abstraction. The domain model and UML class diagram clearly articulated the relationships between the game’s core entities (Game, Team, Player), simplifying code maintenance and communication with stakeholders.  

**What about the process of working through a design document did you find helpful when developing the code?**  
The design document provided a clear structure for implementation, reducing ambiguity. By addressing system constraints (e.g., concurrency, cross-platform compatibility), the document served as a guide for coding practices, testing strategies, and resource allocation.  

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**  
I would revise the evaluation section to include more specific performance metrics and benchmarks for scalability. Incorporating detailed load testing scenarios and expected outcomes would provide a stronger foundation for validating the system's performance under high user traffic.  

**How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?**  
I interpreted the user’s needs by analyzing the requirements for team-based gameplay and platform independence. These needs were reflected in the adoption of a singleton pattern for memory management and the use of cross-platform frameworks like Unity or Flutter. Addressing user needs ensures the software is functional, user-friendly, and aligned with business goals.  

**How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**  
I used a modular approach, dividing the system into smaller, manageable components. The use of UML diagrams and design patterns (e.g., singleton, composition) helped streamline the process. For future projects, I would integrate usability testing earlier and leverage agile methodologies to iterate on feedback more effectively.  
