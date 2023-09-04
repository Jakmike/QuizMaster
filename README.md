Description of the Project:

The project appears to be a web application for conducting quizzes based on questions retrieved from the Open Trivia Database API. Users can access the web application, sort the questions based on various parameters, and then proceed to take an exam that consists of multiple-choice questions. The questions are fetched from the API, stored in a JSON file, and presented to the user during the exam. The user's progress and session are managed through Flask's session management.

Learning Objectives:
1. Building a web application using the Flask framework.
2. Integrating external APIs (Open Trivia Database API) to fetch data.
3. Implementing session management for user authentication and state persistence.
4. Utilizing HTML templates for rendering dynamic content.
5. Handling user interactions and form submissions.
6. Storing and retrieving data from JSON files.


Technologies Used:

- Flask: A Python web framework for building web applications.
- Open Trivia Database API: An API used to retrieve trivia questions.
- Python: The programming language used for the backend logic.
- HTML: Markup language used for rendering web pages.
- JSON: Data format used to store and exchange data between different components.
- Requests library: Used for making HTTP requests to external APIs.
- Session management: Flask's built-in feature for managing user sessions and state.


Third-Party Services Used (if applicable):
There don't appear to be any third-party services explicitly mentioned in the provided code.

Challenges Already Identified:

1. Handling and managing user sessions, including login/logout functionality.
2. Retrieving and displaying questions from the Open Trivia Database API.
3. Implementing proper error handling for API requests and file operations.
4. Ensuring the security of the secret key used for session management.
5. Designing a user-friendly interface for sorting questions and taking the exam.

Schedule of Work (using Trello or Kanban board or other):
Since a specific schedule using Trello or Kanban board isn't provided in the code, I'll outline a hypothetical schedule based on the remaining time (27 days) to complete the project:

Week 1: Project Setup and API Integration

- Set up the Flask application structure.
- Create templates for different pages (index, exam, start, error, etc.).
- Integrate the Open Trivia Database API to retrieve questions.
- Implement sorting functionality for questions.

Week 2: Session Management and User Authentication
- Implement user session management using Flask's built-in mechanisms.
- Create login and logout routes.
- Ensure that user sessions are properly managed and persist across pages.

Week 3: Exam Functionality and JSON Handling
- Design and implement the exam-taking interface.
- Store fetched questions in JSON files.
- Implement functionality to display questions during the exam.
- Handle user responses and calculate results.

Week 4: User Interface Refinement and Testing
- Polish the user interface with CSS and responsive design.
- Test the application thoroughly, including API requests, session management, and user interactions.
- Identify and fix any potential bugs or issues.
- Finalize documentation and prepare for deployment.

Mock-ups (if applicable):
Unfortunately, the provided code doesn't include any mock-ups or visual representations of the user interface. However, a mock-up would typically include designs for the index page, exam page, sorting options, and any other relevant parts of the application. This visual representation would help in understanding the user flow and design expectations.


link to Google Slide: https://docs.google.com/presentation/d/1j2eQM07DhKJBATyQ5-j01uKQNZWGcapi6BK7BnRxQH8/edit?usp=sharing
