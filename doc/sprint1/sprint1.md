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
User Story 1: Task Management for a Fitness Enthusiast
Story: As a fitness enthusiast, I want to organize my to-do items based on my energy levels (e.g., stressed or productive) so that I can manage tasks related to workouts and self-care more effectively.

Acceptance Criteria:
Input field for task description
Dropdown to select task priority (Low Priority or High Priority)
"Add Task" button to submit task data
Tasks categorized in different panels based on priority
Completed tasks move to the "Completed Tasks" panel

Tasks:
1. Set Up Task Input and Priority Selection:
Assigned to: Najwa
Description: Set up JTextField for task input and a dropdown (JComboBox) to select task priority.
Estimation: 2 points (1 hour)

2. Implement "Add Task" Button Functionality:
Assigned to: Abdihakim
Description: Create an "Add Task" button that adds tasks to the appropriate panel based on the selected priority.
Estimation: 2 points (1 hour)

3. Move Task to Completed Panel Upon Completion:
Assigned to: Hamza
Description: Add functionality to move a task to the "Completed Tasks" panel when it is marked as completed.
Estimation: 3 points (1.5 hours)

4. Display Completed Tasks:
Assigned to: Najwa
Description: Ensure completed tasks are displayed in the "Completed Tasks" panel and are disabled to prevent further modification.
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
