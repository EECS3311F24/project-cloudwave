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
