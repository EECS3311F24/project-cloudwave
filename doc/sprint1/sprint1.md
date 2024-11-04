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
User Story 1: User Settings and Password Reset for a Busy Student
Story: As a busy student, I want to be able to reset my password securely so that I can keep my task list private and ensure only I have access to my schedule and to-dos.

Acceptance Criteria:
User settings tab with input fields for current and new password
"Reset Password" button to confirm password change
Confirmation message displayed upon successful password reset
Logout button to return to the login page

Tasks
1. Set Up Current Password Input Field:
Assigned to: Hamza
Description: Set up a JPasswordField for entering the current password in the "User Settings" tab.
Estimation: 1 point (30 minutes)

2. Set Up New Password Input Field:
Assigned to: Najwa
Description: Set up a JPasswordField for entering a new password in the "User Settings" tab.
Estimation: 1 point (30 minutes)

3. Implement Reset Password Functionality:
Assigned to: Abdihakim
Description: Add functionality to validate the current password, update to a new password if correct, and display a confirmation message.
Estimation: 2 points (1 hour)

4. Logout Button Functionality:
Assigned to: Hamza
Description: Implement a logout button that closes the ToDoListPage and opens the LoginPage.
Estimation: 1 point (30 minutes)
Total Estimate for User Story 2: 3 points

User Story 2: Task Management for a Fitness Enthusiast
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



User Story 3: Quick Task Addition for a Working Professional
Story: As a working professional, I want to quickly add high-priority tasks or deadlines under a "Productive" category so that I can manage urgent work commitments efficiently.

Acceptance Criteria:
Input field for task description
Dropdown to prioritize tasks as "Productive" for important work tasks or "Stressed" for less urgent ones
Tasks displayed in the correct category panel based on priority
Completed tasks automatically move to the "Completed Tasks" panel

Tasks

1. Add and Categorize Tasks Based on Priority:
Assigned to: Najwa
Description: Ensure tasks are added to either the "Stressed" or "Productive" panel based on the selected priority.
Estimation: 2 points (1 hour)

2. Move Completed Tasks to "Completed Tasks" Panel:
Assigned to: Abdihakim
Description: Implement functionality to automatically move tasks to the "Completed Tasks" panel when they are marked as completed.
Estimation: 2 points (1 hour)

3. Disable Completed Tasks from Further Editing:
Assigned to: Hamza
Description: Ensure completed tasks are disabled from further modifications once moved to the "Completed Tasks" tab.
Estimation: 1 point (30 minutes)
Total Estimate for User Story 3: 3 points
