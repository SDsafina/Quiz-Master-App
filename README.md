# Quiz-Master-App
Quiz Master is a structured quiz management system designed for admin-led quiz creation and user participation with authentication, role-based access control, and performance tracking through data visualizations.

Technologies Used
 Flask (Python),  Jinja2, SQLite, HTML, CSS, Bootstrap, Flask-Login (session management) 
Purpose of these technologies:
Flask provides a lightweight framework for building web applications.
Jinja2 allows for dynamic rendering of HTML templates.
SQLite is used for efficient, lightweight data storage.
Bootstrap ensures a clean and responsive UI.
DB Schema Design

Reasons for this design:
Ensures data integrity by using foreign keys for linking subjects, chapters, and quizzes.
Follows normalization to prevent redundant data storage.
Allows scalability, ensuring easy expansion for additional features.
Architecture and Features
 


Project Organization:
Controllers (Flask Routes): Located in app.py, handling user authentication, quiz management, and scoring logic.


Templates (Frontend): Stored in the templates/ directory, using Jinja2 for rendering dynamic content.
 
Database Models: Managed in models.py, defining the schema and relationships.


Implemented Features:
User Authentication: Registration, login, and role-based access control.
Quiz Management: Admin can create subjects, chapters, quizzes, and add questions.
User Quiz Attempts: Users can attempt quizzes with real-time score tracking.
Scoring System: Calculates and stores scores based on correct and incorrect answers.
Admin Summary Dashboard: Displays registered user, active quiz, chapters etc..
Search Functionality: Admin can search users, subjects, and quizzes for efficient management. 
