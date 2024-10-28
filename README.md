# Task Board

## Description
Task Board is a project management application that allows team members to manage tasks effectively. Users can add tasks with deadlines, track their progress, and organize them in a user-friendly interface. This application leverages jQuery UI for interactivity and Day.js for date management.

## Features
- **Task Management**: Add, delete, and update tasks.
- **Progress Tracking**: Organize tasks in columns representing their current state: Not Yet Started, In Progress, and Completed.
- **Color Coding**: Tasks are color-coded based on their deadline status (yellow for nearing deadlines and red for overdue tasks).
- **Local Storage**: Tasks persist across page refreshes using localStorage.
- **Drag and Drop**: Easily move tasks between columns using drag-and-drop functionality.

## User Story
AS A project team member with multiple tasks to organize  
I WANT a task board  
SO THAT I can add individual project tasks, manage their state of progress, and track overall project progress accordingly.

## Acceptance Criteria
- The task board displays tasks in columns representing their progress state.
- Each task is color-coded based on its deadline status.
- Users can enter a new task's title, description, and deadline in a modal dialog.
- Saved tasks persist in localStorage.
- Tasks can be dragged to different progress columns and will retain their state after refreshing.
- Tasks can be deleted and will not return upon refreshing.

## Technologies Used
- HTML
- CSS
- JavaScript
- jQuery
- jQuery UI
- Day.js

## Installation
1. Clone the repository:
   
git clone https://github.com/BetsyAssefa/Task-board.git

Usage
Click the "Add Task" button to open the modal dialog.
Enter the task details and click "Save Task" to add it to the board.
Drag tasks between columns to update their progress.
Click the delete button on a task to remove it from the board.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Thanks to my instructors and my classmates for contributing ideas and support.


