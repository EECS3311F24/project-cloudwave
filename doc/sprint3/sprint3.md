Sprint Planning Meeting (sprint3.md)
Sprint Goal:
Complete the implementation of a Task Progression Bar and Reminder Feature in the Moody (to-do list app), ensuring they are fully 
functional, visually integrated, and provide a seamless user experience.

Identified Spikes:
Task Progression Bar Implementation: Researched various approaches for visualizing task progress, including progress bars and 
circular progress indicators. Decided to use a horizontal progress bar that updates as tasks are completed or added.
Evaluated different color schemes to ensure the bar is visually appealing and easy to interpret at a glance.

Reminder Feature Development: We explored various ways to handle task reminders using setTimeout() and setInterval() functions. 
A key challenge was figuring out how to stop overlapping reminders from appearing simultaneously. To solve this, we decided to 
implement a queued notification system that schedules reminders sequentially, ensuring they don’t overlap. 

Team Capacity:
Total available hours per team member: [8 hours/per week/per team member] 
Total: [24 hours/per week]

User Story Decisions:

Task Progression Bar:
Users can view their overall progress with a visual bar showing the percentage of completed tasks.
The bar dynamically updates as tasks are added or marked as complete.

Reminder Feature:
Users receive timely reminders for incomplete tasks.
Reminders are triggered based on due times set by the user and persist across sessions.

Task Breakdown:

Feature 1: Task Progression Bar
Backend:
Develop a method to calculate the percentage of completed tasks based on total tasks.
Implement logic to update the progress value whenever tasks are added, completed, or removed.

Frontend:
Create a visual progress bar that displays the percentage of completed tasks.
Ensure the progress bar updates as users interact with tasks (add, complete, or delete).

Testing:
Write unit tests to verify that the progress calculation is accurate and updates correctly.
Test the UI to ensure the progress bar visually reflects task status changes immediately.

Feature 2: Reminder Feature
Backend:
Extend the Task class to include a reminderTime field for setting reminders.
Implement a queued notification system to prevent overlapping reminders using setTimeout().

Frontend:
Add a user-friendly input for setting reminder times when creating or editing tasks.
Display notification pop-ups at the scheduled reminder times, ensuring they are clear.

Testing:
Write unit tests to ensure reminders trigger correctly at the specified times without overlap.

User Stories

Story 1:

Acceptance Criteria:  

Tasks:  

Story 2:


Acceptance Criteria:  

Tasks:  

Story 3:


Acceptance Criteria:  

Tasks:  
