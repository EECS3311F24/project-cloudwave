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

Story 1: Task Progression Bar for Design Tasks
As a product designer,
I want a task progression bar to show the percentage of completed design tasks,
so that I can track the progress of my project milestones and ensure deadlines are met.

Acceptance Criteria:

A progression bar is displayed at the top of the task list.
The bar dynamically updates as design tasks are marked as complete or incomplete.
The percentage of completion is shown alongside the progression bar.

Tasks:

Create Task Progression Bar Component

Description: Design and implement a visual progression bar that calculates and displays the percentage of completed design tasks.
Estimation: 2 points (1 hour)
Link Progression Bar to Task Completion

Assigned to: Hamza
Description: Update the progression bar dynamically whenever a task is marked as complete or incomplete.
Estimation: 2 points (1 hour)
Test and Validate Progression Bar Functionality

Assigned to: Abdihakim
Description: Test the progression bar with different numbers of tasks and ensure it accurately reflects the completion percentage.
Estimation: 1 point (30 minutes)
Total Estimate for User Story 1: 5 points

Story 2: Study Task Reminder System
As a university student preparing for exams,
I want to receive reminders for tasks related to my study schedule,
so that I can prioritize reviewing important topics before exams and avoid falling behind.

Acceptance Criteria:

Users can set deadlines when creating or editing study-related tasks.
Notifications are sent for tasks due within a set time frame (e.g., 1 hour or 1 day before the deadline).
Notifications include the task name, deadline, and options to snooze or mark the task as complete.
Tasks:

Add Deadline Input for Study Tasks

Assigned to: Hamza
Description: Allow users to set or edit deadlines for study tasks when creating or updating tasks. Display the deadline in the task list.
Estimation: 2 points (1 hour)
Implement Reminder Notification System

Assigned to: Najwa
Description: Create a notification system that alerts users when a task deadline is approaching, including the task name and options to snooze or mark it as complete.
Estimation: 2 points (1 hour)
Design Snooze and Complete Options for Notifications

Assigned to: Abdihakim
Description: Add functionality to snooze reminders or mark tasks as complete directly from the notification.
Estimation: 2 points (1 hour)
Test Reminder System for Accuracy

Assigned to: Najwa
Description: Test the reminder system with various deadlines to ensure notifications appear at the correct time and include the correct information.
Estimation: 1 point (30 minutes)
Total Estimate for User Story 2: 7 points

Story 3: Task Categorization System
As a freelance graphic designer,
I want to organize my tasks into different categories,
so that I can easily separate client projects, personal tasks, and administrative work.

Acceptance Criteria:

Users can assign tasks to predefined or custom categories (e.g., "Work," "Personal," "Urgent").
Tasks are visually grouped or filtered by category in the task list.
Users can create, edit, or delete custom categories.
Tasks:

Add Category Selection for Tasks

Assigned to: Hamza
Description: Allow users to assign tasks to a category during task creation or editing. Display the category next to the task name in the list.
Estimation: 2 points (1 hour)
Design and Implement Category Filters

Assigned to: Najwa
Description: Create a dropdown or tabbed interface for filtering tasks by category. Ensure tasks are grouped visually when no filter is selected.
Estimation: 2 points (1 hour)
Enable Custom Category Management

Assigned to: Abdihakim
Description: Allow users to create, rename, and delete custom categories. Ensure changes to categories are reflected in the task list.
Estimation: 2 points (1 hour)
Test Category Functionality

Assigned to: Najwa
Description: Test the ability to assign, filter, and manage categories. Ensure tasks update dynamically when categories change.
Estimation: 1 point (30 minutes)
Total Estimate for User Story 3: 7 points
