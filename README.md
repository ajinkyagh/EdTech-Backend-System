
# EdTech Backend System**

## Overview**
This project is a backend system for an EdTech platform, built with Python. It provides core functionalities for managing users, courses, and learning activities. The system is designed with an object-oriented approach, making it modular and scalable for future enhancements like database integration or API endpoints.

## Features
* User Management**
  * Create and manage users (Learners, Instructors)
  * Update credentials with validation
  * Secure password checks
* Course Management
  * Enroll and drop courses
  * Track enrolled and completed courses
* Progress Tracking
  * Manage learner progress and completions
* Assessment Handling
  * Basic structure for quizzes and grading (if implemented in the file)

## Tech Stack**
* Language: Python 3.x
* Paradigm: Object-Oriented Programming (OOP)
* Tools: Jupyter/Colab for development

## System Design**
The application follows an object-oriented design pattern:
* User: Base class for all users
* Learner: Extends `User`, adds enrollment and course management
* Instructor: Extends `User`, includes course creation (if implemented)
* Course: Represents course entities with attributes like title and description
* Quiz: Represents assessment structure (if present)

This modular design makes it easy to integrate with databases, REST APIs, or front-end systems in the future.

## How to Run**

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/edtech-backend-system.git
   cd edtech-backend-system
   ```
2. Run the Python script:

   ```bash
   python edtech_backend_system.py
   ```
3. Interact with the classes in a Python shell or notebook.

## Sample Usage**

```python
# Create a learner
learner = Learner(1, "Alice", "alice@example.com", "securePass123")

# Enroll in a course
learner.enroll_in_course("CS101")

# Update email
learner.update_email("alice_new@example.com")
```

## What I Learned**

* Object-Oriented Design:** Implemented inheritance and encapsulation for reusable components.
* Data Validation:** Built secure input handling for user credentials.
* Scalability:** Designed the system for future API and database integration.

## Future Improvements
* Add a database (e.g., SQLite, PostgreSQL) for persistent storage.
* Develop REST API endpoints using Flask or FastAPI.
* Implement JWT-based authentication.
* Build a front-end interface for learners and instructors.


