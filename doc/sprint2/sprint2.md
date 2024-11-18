Sprint Planning Meeting (sprint2.md)
Sprint Goal:
Complete the implementation of Timer Structure and Due Date Functionality for tasks in the Moody(to-do list app), 
ensuring both are fully integrated and working seamlessly.

Identified Spikes:
Research on Timer Libraries and Frameworks: We explored various libraries and built-in JavaScript functions for 
managing task durations. The goal was to implement a timer that could start, pause, and reset efficiently while 
ensuring persistence across app restarts. After evaluating different options, we decided to use setInterval() for 
its flexibility and minimal overhead, while also implementing backend storage to persist timer states across sessions.

Integrating Due Date Functionality: We focused on the best approach for allowing users to set due dates for their tasks. 
Research included exploring different calendar and date-picking libraries to provide an intuitive interface for selecting 
due dates. The goal was to integrate a calendar input into the UI, allowing users to easily set and view due dates for tasks, 
ensuring that tasks could be organized by deadlines without implementing additional reminder or notification features.

Team Capacity:
Total available hours per team member: [8 hours/per week/per team member] 
Total: [24 hours/per week]

User Story Decisions:
Timer Structure: Enable users to track how much time they spend on individual tasks, with start, pause, and reset options.
Due Date Functionality: Allow users to set deadlines for tasks, with notifications sent when tasks are approaching or overdue.

Task Breakdown:
Feature 1: Timer Structure
-Backend:
  -Develop a Timer class to manage the start, pause, and reset functionality of the task timer.
  -Implement a method to track the duration of each task.
  -Store time logs in the database to allow users to view time spent on tasks.

-Frontend:
  -Integrate a visual timer UI element that shows time elapsed for a task.
  -Implement buttons for start, pause, and reset on the task detail page.

-Testing:
  -Write unit tests to verify that the timer starts, pauses, and resets correctly.
  -Test the time logging to ensure it stores accurate data for each task.

Feature 2: Due Date Functionality
-Backend:
  -Extend the Task class to include a dueDate field.
  -Implement a reminder system to notify users of upcoming or overdue tasks.
  -Write backend logic to calculate overdue tasks and trigger reminders.

-Frontend:
  -Add a calendar input to allow users to select a due date when creating or editing a task.
  -Display the due date next to each task on the main task list page.
  -Implement a countdown feature that shows how much time is left until the due date.

-Testing:
  -Write tests to validate that tasks with due dates trigger reminders correctly.
  -Test the calendar input for due date selection.


User Stories

Story:
As a volunteer event organizer, I want to add due dates to my tasks so that I can track event preparation deadlines and ensure everything is completed on time.

Acceptance Criteria:  A calendar option to select a due date when creating a task. The due date is shown next to tasks in the task list. Tasks that are due soon (within 24 hours) are visually highlighted.

Tasks:  Add a Calendar Option for Due Date Selection:  Assigned to: Najwa Description: Implement a calendar button or dropdown to let users choose a due date when creating or editing a task. Ensure the selected date is saved with the task. Estimation: 2 points (1 hour) Show Due Dates and Highlight Tasks Due Soon:  Assigned to: Hamza Description: Display the due date next to each task in the task list. Add a visual indicator (e.g., color or icon) to highlight tasks due within the next 24 hours. Estimation: 2 points (1 hour) Test and Ensure Due Date Functionality Works:  Assigned to: Abdihakim Description: Test that users can add, see, and edit due dates. Verify that tasks due soon are highlighted properly. Estimation: 1 point (30 minutes) Total Estimate for User Story 1: 5 points

Story:
As a freelancer, I want a timer feature to schedule breaks so that I can maintain productivity and manage my work-life balance effectively.

Acceptance Criteria:  Countdown timer for preset break durations (e.g., 5, 10, 15 minutes). Start, pause, and reset buttons to control the timer. A notification sound when the break ends.

Tasks:  Develop Countdown Timer:  Assigned to: Abdihakim Description: Implement a timer feature with countdown functionality for preset durations. Estimation: 2 points (1 hour) Design Timer Control Buttons:  Assigned to: Najwa Description: Create "Start," "Pause," and "Reset" buttons for the timer. Estimation: 1 point (30 minutes) Set Up Break End Notification:  Assigned to: Hamza Description: Add a notification sound and message when the timer ends. Estimation: 1 point (30 minutes)

Story:
As a parent managing family tasks, I want to update the due dates of existing tasks so that I can accommodate changes in plans or priorities.

Acceptance Criteria:  An "Edit Due Date" button available for each task. A date picker for selecting a new due date. A confirmation message displayed upon successfully updating the due date.

Tasks:  Add "Edit Due Date" Button:  Assigned to: Hamza Description: Add a button to the task list interface to allow editing of due dates. Estimation: 1 point (30 minutes) Implement Date Picker for Editing:  Assigned to: Najwa Description: Integrate the date picker for selecting a new due date when the "Edit Due Date" button is clicked. Estimation: 2 points (1 hour) Update Task with New Due Date:  Assigned to: Abdihakim Description: Modify the selected task in the task list to display the updated due date. Estimation: 1 point (30 minutes) Total Estimate for User Story 3: 4 points






