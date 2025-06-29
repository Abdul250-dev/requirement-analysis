# Requirement Analysis in Software Development.
This repository is created to collect, organize, and document the system requirements for an Airbnb booking platform. It serves as the foundational step in planning and designing the system's architecture.

# What is Requirement Analysis?
Requirement Analysis is a foundational phase in the Software Development Lifecycle (SDLC) where developers, analysts, and stakeholders gather, evaluate, and document the needs and expectations of end-users for a software system. The goal is to clearly define what the system should do, how it should behave, and what constraints it must operate within — all before actual development begins.

# Why is Requirement Analysis Important? 

Requirement Analysis is one of the most essential phases in the Software Development Lifecycle (SDLC). It sets the direction for the entire project and helps ensure the final product aligns with user needs and business goals.

1. 🎯 Clarifies Project Scope and Objectives
Requirement analysis helps all stakeholders—clients, users, and developers—reach a shared understanding of what the system should do. This reduces confusion, ensures everyone is aligned, and prevents scope creep (the uncontrolled expansion of project goals).

2. 💸 Minimizes Costly Rework
Identifying and addressing requirements early in the SDLC is much cheaper and more efficient than making changes later during development or after deployment. Requirement analysis helps detect gaps, conflicts, or unrealistic expectations early on.

3. 📊 Guides Design, Development, and Testing
Requirements serve as the foundation for system design, architecture, and testing plans. Clear and well-documented requirements ensure that developers build the right functionality and testers can validate it against the agreed criteria.

# Key Activities in Requirement Analysis.

Requirement Analysis involves several interconnected activities that ensure software requirements are complete, clear, and actionable. Below are the five key activities in this process:

🔹 1. Requirement Gathering
- Involves collecting initial information about the system’s purpose, target users, and business goals.
- Stakeholders such as clients, users, developers, and project managers are identified and engaged.
- Methods include reviewing existing documentation, conducting feasibility studies, and understanding current systems (if applicable).

🔹 2. Requirement Elicitation
- Focuses on actively extracting detailed requirements from stakeholders through interactive techniques.
- Techniques include interviews, surveys, brainstorming sessions, focus groups, workshops, and observation.
- The aim is to uncover both explicit needs and implicit expectations that may not be clearly stated.

🔹 3. Requirement Documentation
- Translates gathered and elicited information into a structured format that can be easily reviewed and shared.
- Includes the creation of Software Requirement Specifications (SRS), user stories, or use case diagrams.
- Ensures that requirements are recorded accurately, unambiguously, and traceably for future reference.

🔹 4. Requirement Analysis and Modeling
- Involves refining, categorizing, and prioritizing requirements for technical feasibility and business alignment.
- Identifies inconsistencies, duplicates, or conflicts among the requirements.
- May include visual modeling using tools like flowcharts, entity-relationship diagrams (ERDs), data flow diagrams (DFDs), or UML.

🔹 5. Requirement Validation
- Ensures that documented requirements are correct, complete, and meet stakeholder expectations.
- Techniques include review meetings, walkthroughs, prototyping, and formal approval from stakeholders.
- Prevents misunderstandings that could lead to project delays or product failures.

📎 Together, these five activities ensure that the software is designed to meet real needs, reducing the risk of rework, cost overruns, and user dissatisfaction.

# Types of Requirements.

Functional vs. Non-functional Requirements

In software engineering, requirements are generally categorized into two main types: Functional Requirements and Non-functional Requirements. Both are essential to the successful design and implementation of a system, but they address different aspects

✅ Functional Requirements

📘 Definition:
Functional requirements describe what the system should do. They define specific behaviors, features, or functions the software must perform to meet user needs and achieve business objectives. (What the system should do)

🛠️ Examples in a Booking Management System:
Users should be able to search for available properties based on location, date, and number of guests.

- A guest can create an account and log in securely.
- A host should be able to list a new property with details such as price, photos, and availability.
- The system should send a confirmation email after a booking is made.
- Users can cancel or modify reservations within the allowed policy period.

⚙️ Non-functional Requirements
📘 Definition:
Non-functional requirements describe how the system should behave. They refer to the quality attributes, performance standards, or operational constraints of the system, rather than specific behaviors. (How the system should behave)

🛠️ Examples in a Booking Management System:

- The system should respond to search queries within 2 seconds (Performance).
- The platform must be available 99.9% of the time during a calendar year (Availability).
- All user data must be encrypted in transit and at rest (Security).
- The application should be scalable to support thousands of concurrent users (Scalability).
- The user interface must be accessible on both mobile and desktop devices (Usability).

# Use Case Diagrams (./alx-booking-uc.png)

📘 What is a Use Case Diagram?
A Use Case Diagram is a visual representation of the interactions between users (actors) and a system. It shows the functional requirements of a system and highlights what the system should do from a user’s perspective. Use case diagrams are part of the Unified Modeling Language (UML) and are commonly used during the early phases of software development, especially in requirement analysis.

Each use case represents a specific goal the user wants to achieve using the system, such as “Book a Property” or “List a New Property.”

🧠 Benefits of Use Case Diagrams
✅ Clarifies System Scope
Helps define what the system will (and won’t) do, avoiding scope creep.

✅ Identifies Key User Interactions
Makes it easier to understand who interacts with the system and what they can do.

✅ Improves Communication
Serves as a common language between developers, business analysts, and stakeholders.

✅ Supports Requirement Gathering
Acts as a starting point for identifying and organizing functional requirements.

✅ Visual Simplicity
Easily illustrates complex processes in a clear and intuitive way.

# Use Case Diagrams.

📘 What is a Use Case Diagram?
A Use Case Diagram is a visual representation of the interactions between users (actors) and a system. It shows the functional requirements of a system and highlights what the system should do from a user’s perspective. Use case diagrams are part of the Unified Modeling Language (UML) and are commonly used during the early phases of software development, especially in requirement analysis.

Each use case represents a specific goal the user wants to achieve using the system, such as “Book a Property” or “List a New Property.”

 Benefits of Use Case Diagrams
✅ Clarifies System Scope
Helps define what the system will (and won’t) do, avoiding scope creep.
✅ Identifies Key User Interactions
Makes it easier to understand who interacts with the system and what they can do.
✅ Improves Communication
Serves as a common language between developers, business analysts, and stakeholders.
✅ Supports Requirement Gathering
Acts as a starting point for identifying and organizing functional requirements.
✅ Visual Simplicity
Easily illustrates complex processes in a clear and intuitive way.

Use Case in a Booking System 
In a booking management platform![alx-booking-uc](https://github.com/user-attachments/assets/ab45978f-fee6-498c-af62-6efb608128c2)
 like AirBnB, some typical use cases include:
- Guest: Search for Properties, Make a Reservation, Cancel Booking
- Host: List Property, Update Availability, View Bookings
- Admin: Approve Listings, Manage Users


# Acceptance Criteria
📘 What is Acceptance Criteria?
Acceptance Criteria (AC) are specific, measurable conditions that a software feature or user story must meet to be considered complete and acceptable by stakeholders. It acts as a checklist that ensures the delivered functionality meets the original intent and expectations.

🛠️ How to Establish Acceptance Criteria
To create effective acceptance criteria:

Collaborate with stakeholders – Work closely with clients, product owners, or users to understand their expectations.

Use clear and simple language – Avoid technical jargon unless necessary; write for both business and technical audiences.
Follow a structured format – Common formats include:
Gherkin syntax (Given–When–Then)
Checklist format (bullet points)
Make it testable – Each criterion should be measurable and able to be confirmed through functional or user acceptance testing.

🔍 Importance of Acceptance Criteria in Requirement Analysis
✅ Clarifies Scope: It removes ambiguity by defining exactly what “done” means for each feature or task.
✅ Guides Development: Developers use it as a target when designing and coding features.
✅ Improves Communication: It creates a shared understanding between clients, developers, testers, and business analysts.
✅ Supports Testing: QA/testers use acceptance criteria to write user acceptance tests (UAT).
✅ Reduces Rework: Prevents misunderstandings that can lead to missing functionality or redesigns.

🧾 Feature: Create Account
🎯 User Story:
As a new user, I want to create an account so I can log in and use the platform’s features.

✅ Acceptance Criteria (Given–When–Then):
- Given a new user visits the registration page,
When they enter all required fields and submit the form,
Then the system creates the account and redirects them to their dashboard.

- Given a user tries to register with an existing email,
When the form is submitted,
Then the system shows a validation error message.

- Given the user leaves the required fields blank,
When they click "Sign Up",
Then the form highlights the missing inputs.

✅ Acceptance Criteria (Checklist Format):
 Form includes name, email, password, and optional phone number.

 Password must meet security criteria (e.g., 8+ characters, special symbol).

 Duplicate email addresses are rejected.
 The system validates input before submission.
 Successful registration redirects the user and sends a welcome email.
