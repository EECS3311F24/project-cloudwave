Sprint Goal:
Complete the foundational features of the calendar app, focusing on user sign-up, event creation, and event viewing. 

Spikes:

Spike 1: UI Design and Component Selection
Investigate and decide on the Java Swing components (such as JList, JCheckBox, and JButton) that will be used for event and task management. Ensure they meet the functional requirements for user interaction.

Spike 2: User Data Storage Options
Investigate and decide on the best method for storing user data (e.g., sign-up and login information) locally. Options include plain text files, serialized Java objects, or a lightweight embedded database (e.g., SQLite).

Spike 3: Event Data Structure
Explore and define the most efficient data structure for storing events and tasks. This might involve deciding between lists, arrays, or other data structures based on accessibility and potential sorting needs.

Participants/Team Capacity Recording:
All Team members have been present during our set meeting time for every week and made equal contributions. 
Team Capacity: Each member spent at least 10 hours on the project. 

User Stories for Sprint 1:

User Story 1: User Sign-Up
- Story: As a fitness enthusiast, I want to sign up by entering my name and email so that I can have a personalized experience with the app and track my progress.
- Acceptance Criteria:
  - Input fields for name and email
  - "Sign Up" button to submit
  - Data is saved locally in a text file
  - Confirmation message displayed upon successful sign-up

Tasks

Task 1: Set up JTextField input fields for username and password.
- Assigned to: Najwa
- Estimation: 2 points (1 hour)

Task 2: Create a "Login" button for submitting user data.
- Assigned to: Abdihakim
- Estimation: 1 point (30 minutes)

Task 3: Implement functionality to save user data (username and password) to a text file.
Assigned to: Hamza
Estimation: 3 points (1.5 hours)

Task 4: Display a confirmation message upon successful sign-up (e.g., using JOptionPane).
Assigned to: Najwa
Estimation: 1 point (30 minutes)
Total Estimate for User Story 1: 3 points

User Story 2: Basic Event Creation
- Story: As a busy student, I want to add events to specific days in my calendar so that I can keep track of important deadlines and manage my schedule effectively.
- Acceptance Criteria:
  - Date selection for event creation
  - Pop-up window for event details (name, date, and time)
  - Event details saved in an array or list
  - Events displayed on the selected date in the calendar

Tasks

Task 1: Enable date selection to create an event.
Assigned to: Hamza
Estimation: 2 points (1 hour)

Task 2: Set up a pop-up to enter event details (name and priority).
Assigned to: Abdihakim
Estimation: 2 points (1 hour)

Task 3: Save event details to an array or list.
Assigned to: Najwa
Estimation: 2 points (1 hour)

Task 4: Display events 
Assigned to: Hamza
Estimation: 3 points (1.5 hours)
Total Estimate for User Story 2: 4 points

User Story 3: Quick Event Addition for Busy Professionals
- Story: As a working professional with a busy schedule, I want to quickly add and view
  important work events or deadlines in my calendar so that I can effectively plan my day and avoid missing any deadlines.
- Acceptance Criteria:
  - The user can select a specific date in the calendar view.
  - A pop-up (e.g., using JOptionPane) allows the user to enter details like event name and time.
  - After confirming, the event is saved and displayed in the calendar view on the selected date.
  - If the user tries to save an event without entering both the event name and time, an error message prompts them to complete all fields.

Tasks:

Task 1: Develop a date selection feature within the calendar view.
Assigned to: Najwa
Estimation: 2 points (1 hour)

Task 2: Add a pop-up for entering event name and time.
Assigned to: Abdihakim
Estimation: 2 points (1 hour)

Task 3: Write functionality to save event details to a calendar list.
Assigned to: Hamza
Estimation: 3 points (1.5 hours)

Task 4: Display saved events on selected dates in the calendar view.
Assigned to: Najwa
Estimation: 2 points (1 hour)

Task 5: Implement error handling for incomplete fields (event name and time).
Assigned to: Abdihakim
Estimation: 1 point (30 minutes)

Total Estimate for User Story 2: 10 points
