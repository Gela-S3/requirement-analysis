# requirement-analysis



# What is Requirement Analysis?

Requirement Analysis is a crucial phase in the software development lifecycle (SDLC) where the needs and expectations for a new software system are identified, documented, and analyzed. Think of it as the blueprint stage before construction begins. Instead of just jumping into building, you take the time to figure out exactly what you're going to build, why you're building it, and who it's for.

This process involves gathering requirements from all stakeholders—the people who have an interest in the project, such as clients, end-users, and project managers. These requirements are then carefully scrutinized to ensure they're clear, complete, and consistent. The ultimate goal is to create a comprehensive and accurate Software Requirements Specification (SRS) document, which serves as a formal agreement between the developers and the stakeholders.



# Importance in the SDLC

Requirement analysis is arguably the most critical part of a project's success. Getting it right from the start can save a project from major headaches and failures. Here's why it's so important:



# Prevents Scope Creep: 

By clearly defining the project's boundaries upfront, requirement analysis helps prevent scope creep—the uncontrolled expansion of project requirements. A solid, agreed-upon scope means any new requests can be properly evaluated and managed, avoiding delays and budget overruns.



# Reduces Rework and Cost: 

Errors and misunderstandings caught in the analysis phase are far cheaper to fix than those discovered during coding or testing. A clear set of requirements means developers don't waste time building the wrong features, which significantly reduces the need for costly rework.



# Aligns Stakeholders: 

The process forces everyone to get on the same page. It ensures that the development team's understanding of the system aligns perfectly with the stakeholders' vision and expectations.



# Forms the Foundation for Design and Testing: 

The documented requirements serve as the foundation for all subsequent phases. The system's design is built directly from the requirements, and test cases are written to verify that each requirement has been correctly implemented. Without a strong foundation, the rest of the development process is built on shaky ground.

### Why is Requirement Analysis Important?




### Key Activities in Requirement Analysis

Requirement Analysis is a comprehensive process that involves several key activities to ensure a clear understanding of what a software system must accomplish. Here are the five main activities involved:

- Requirement Gathering: This is the initial phase where information is collected from all relevant stakeholders. This involves understanding their needs, goals, and expectations for the system. Methods often include interviews, surveys, and workshops.

- Requirement Elicitation: This activity is about actively discovering and drawing out both explicit and implicit requirements. It goes beyond simple gathering by using techniques like prototyping and brainstorming to help stakeholders articulate needs they may not have initially considered.

- Requirement Analysis and Modeling: Once requirements are gathered, this activity focuses on examining, organizing, and structuring them. The goal is to identify and resolve any conflicts, ambiguities, or missing information. Diagrams and models, such as Use Case Diagrams and data flow diagrams, are often created to visualize how the system will work.

- Requirement Documentation: This is the process of formally writing down all the analyzed and agreed-upon requirements. The output is a Software Requirements Specification (SRS) document, which serves as a formal contract between the development team and the stakeholders, detailing all functional and non-functional requirements.

- Requirement Validation: The final activity is to review and confirm that the documented requirements are accurate, complete, and feasible. This is a critical step where stakeholders and developers check the SRS document to ensure it reflects their true needs and expectations before the project moves into the design and development phases.


Types of Requirements"


Functional Requirements
Functional requirements define what the system must do. They are the specific behaviors and functions of the software, often expressed as user stories or system-level features. These are the core capabilities that a user can directly interact with.

Examples for the Restaurant Booking Management System:

The system must allow a customer to search for available tables by date, time, and party size.

The system must allow a customer to reserve a table, providing their name, contact information, and special requests.

The system must send a confirmation email or SMS to the customer after a booking is successfully made.

The system must allow restaurant staff to view, create, edit, and cancel bookings.

Non-functional Requirements
Non-functional requirements describe how the system performs a certain function. They are constraints on the system's qualities, such as performance, security, usability, and reliability. These requirements are critical for the user experience but are not directly tied to a specific function.

Examples for the Restaurant Booking Management System:

Performance: The system must respond to a table search query within 2 seconds, even during peak hours.

Usability: The booking interface must be intuitive and easy for a first-time user to complete a reservation in under 90 seconds.

Security: Customer data, including names and contact information, must be encrypted and protected against unauthorized access.

Reliability: The system must have a 99.9% uptime and be available 24/7 for customers to make reservations.



Use Case Diagrams
Use Case Diagrams are a powerful tool in Unified Modeling Language (UML) for visualizing the functionality of a system from the perspective of its users. They illustrate the relationships between actors (users or other systems) and the use cases (the specific functions or services the system provides).

Benefits of Use Case Diagrams:

High-Level View: They provide a simple, high-level overview of a system's functionality, making it easy for both technical and non-technical stakeholders to understand its scope.

Defines Boundaries: They clearly define the boundaries of the system and what it is intended to do.

Identifies Actors: They help identify all the different types of users and external systems that will interact with the software.

Example Use Case Diagram for the Restaurant Booking System
Below is a representation of the use case diagram for the restaurant booking system, illustrating the key actors and their interactions with the system's functions.

Actors:

Customer: An individual who wants to make a booking.

Restaurant Staff: An employee who manages bookings and tables.

System (external): Represents an external service, such as an SMS or email service, that the system interacts with.

Use Cases:

Search for Tables

Make a Booking

Receive Confirmation

View Bookings

Manage Bookings (create/edit/cancel)



Acceptance Criteria