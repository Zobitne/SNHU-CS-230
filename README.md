# SNHU-CS-230 / CS 230, Operating Platforms

My final prokect for CS 230.

1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
   
• The client for this project was The Gaming Room. They wanted to expand their existing Android game, Draw It or Lose It, into a web-based, multi-platform application. The system needed to support multiple teams and players, enforce unique names and identifiers, and operate in a distributed environment. The goal was to design a scalable and maintainable solution that could run across different operating systems while maintaining consistent performance and reliability.

2. What did you do particularly well in developing this documentation?

• I believe I did particularly well in clearly structuring the design document and aligning each technical decision with a specific requirement. Instead of just describing features, I connected design patterns, system architecture, operating platform choices, and security considerations directly back to the client’s needs. The progression from requirements to constraints to architecture made the document cohesive rather than fragmented.

3. What about the process of working through a design document did you find helpful when developing the code?

• Working through the design document before implementation made the coding process much clearer. Breaking the system down into architecture, domain models, and platform evaluations forced me to think about scalability, memory management, distributed systems, and security early on. That structure reduced ambiguity and made later technical decisions easier because the foundation had already been defined.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

• If I were to revise one part of the project, I would strengthen the early architectural diagrams and possibly include more detailed visual modeling. While the written explanations were clear, adding more visual representation of distributed components and system flow would improve communication for stakeholders who prefer diagrams over technical text.

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

• I interpreted the client’s needs by focusing on scalability, uniqueness constraints, distributed access, and security. For example, the requirement that only one game instance exist in memory led to the use of the Singleton pattern. The need for cross-platform access influenced the decision to use a web-based client-server architecture. Considering user needs is critical because design decisions must solve real problems, not just demonstrate technical knowledge. Without grounding decisions in user requirements, the system risks becoming overly complex or misaligned with business goals.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

• My approach to designing the software involved starting with requirements, identifying constraints, selecting appropriate design patterns, and then evaluating operating platforms and deployment environments. I focused on separation of concerns, scalability, and maintainability. In the future, I would continue using structured documentation early in the process, along with architectural comparisons and risk analysis, before beginning implementation. This approach ensures that the solution is technically sound and aligned with the client’s objectives.
