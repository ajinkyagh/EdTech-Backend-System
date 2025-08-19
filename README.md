# EdTech Backend System

A Python-based backend system for an EdTech platform. The project demonstrates how to design scalable, object-oriented applications for managing learners, instructors, courses, and assessments. It serves as a foundation for extending into production-ready systems with databases, REST APIs, and front-end integration.

---

## Project Overview

**Objectives**

* Build a modular backend for an education platform
* Demonstrate object-oriented design in Python
* Implement user, course, and progress management features
* Provide a base for future enhancements such as APIs and persistent storage

**Why This Project Matters**

* Models real-world challenges faced by EdTech platforms
* Highlights OOP principles applied to backend design
* Showcases ability to design scalable, extensible systems

---

## Features

* **User Management**

  * Create and manage users (Learners, Instructors)
  * Update user details with validation and secure password checks

* **Course Management**

  * Enroll and drop courses
  * Track enrolled and completed courses

* **Progress Tracking**

  * Record learner progress and completions

* **Assessment Handling**

  * Extendable structure for quizzes and grading

---

## System Design

The project uses an object-oriented design pattern:

* **User** – Base class for all users
* **Learner** – Extends `User`; manages enrollment and course interactions
* **Instructor** – Extends `User`; includes course creation and teaching features
* **Course** – Represents course entities (title, description)
* **Quiz** – Basic assessment representation (if implemented)

This modular design allows for:

* Easy integration with **databases** (e.g., SQLite, PostgreSQL)
* Development of **REST APIs** using Flask or FastAPI
* Future **front-end integration**

---

## Tech Stack

| **Category** | **Tools & Technologies**          |
| ------------ | --------------------------------- |
| Language     | Python 3.x                        |
| Paradigm     | Object-Oriented Programming (OOP) |
| Development  | Jupyter Notebook, Google Colab    |

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/edtech-backend-system.git
   cd edtech-backend-system
   ```

2. Run the script:

   ```bash
   python edtech_backend_system.py
   ```

3. Test the classes in Python or Jupyter Notebook.

---

## Sample Usage

```python
# Create a learner
learner = Learner(1, "Alice", "alice@example.com", "securePass123")

# Enroll in a course
learner.enroll_in_course("CS101")

# Update email
learner.update_email("alice_new@example.com")
```

---

## Key Learnings

* Applied **inheritance, encapsulation, and polymorphism** to real-world use cases
* Designed with **scalability in mind** for future APIs and databases
* Implemented **data validation and secure input handling**
* Practiced writing clean, modular, and extensible Python code

---

## Future Enhancements

* Add persistent storage with SQLite or PostgreSQL
* Develop REST APIs with Flask or FastAPI
* Implement JWT-based authentication for security
* Build a front-end interface for learners and instructors

---

## Portfolio Value

This project demonstrates:

* Strong foundation in **object-oriented programming**
* Ability to design **modular backend systems**
* Practical application of **Python for backend development**
* Readiness to extend projects into **production-grade applications**

---

Would you like me to also **add a “Projects Index” section at the bottom** of this README (linking to your other repos like *Medalyze*, *HR Dashboard*, *Goodwill Dashboard*) so anyone visiting your GitHub sees a curated portfolio instead of just a single project?
