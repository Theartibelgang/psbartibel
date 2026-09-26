#StudyTask: A Simple Student Task and Deadline Tracker

StudyTask is a simple, smart app concept designed to help Pisay students keep track of their academic workload. Instead of managing assignments by memory or writing deadlines on scattered sheets of paper, this app centralizes your tasks, tracks completion statuses, and helps you prioritize pending work.

This repository holds the initial project structure and draft proposal for our CS2 project.

I. Project Title
StudyTask: A Simple Student Task and Deadline Tracker
II. Problem Statement
Students in Pisay often have several assignments, projects, quizzes, and other school tasks to complete. Because of this, some students may forget deadlines or have difficulty keeping track of which tasks they need to finish first. Writing tasks on different pieces of paper or remembering everything mentally can also make it harder to organize schoolwork.

This project aims to create a simple task and deadline tracker that students can use to organize their school requirements. The program will allow users to enter their tasks, subjects, deadlines, and completion status. It will then display the tasks in an organized way so students can easily see what they still need to accomplish.

This problem is important because better organization can help students keep track of their responsibilities and reduce the chance of forgetting important school tasks.

III. Project Objectives
To create a simple program that allows students to record at least 10 school tasks with their subject, task name, and deadline.
To allow users to mark tasks as completed or incomplete so they can easily monitor their progress.
To provide an organized list of pending tasks that students can check whenever they need to review their school requirements.

IV. Planned Features
The program will have the following features:
Add a new school task.
Enter the subject of the task.
Enter the task name or description.
Enter the deadline.
Display all saved tasks.
Mark a task as completed.
Display pending and completed tasks separately.
Allow the user to exit the program.

V. Planned Inputs and Outputs
Inputs
The user will provide:
Subject name
Task or assignment name
Deadline
Task number when marking a task as completed
User's menu choice
Outputs
The system will display:
List of school tasks
Subject and task names
Deadlines
Completion status
List of pending tasks
List of completed tasks
Confirmation messages when a task is added or completed
Error messages when an invalid choice is entered
VI. Logic Plan – Pseudocode
START

Display the main menu:
1. Add Task
2. View Tasks
3. Mark Task as Completed
4. View Pending Tasks
5. View Completed Tasks
6. Exit

Ask the user to choose an option.

IF the user chooses "Add Task":
    Ask for the subject name.
    Ask for the task name.
    Ask for the deadline.
    Save the task as incomplete.
    Display a confirmation message.

ELSE IF the user chooses "View Tasks":
    Display all saved tasks.
    Display the subject, task name, deadline, and status.

ELSE IF the user chooses "Mark Task as Completed":
    Display the saved tasks.
    Ask the user to select a task.
    Change the selected task's status to completed.
    Display a confirmation message.

ELSE IF the user chooses "View Pending Tasks":
    Display all tasks that are still incomplete.

ELSE IF the user chooses "View Completed Tasks":
    Display all tasks that are completed.

ELSE IF the user chooses "Exit":
    Display a goodbye message.
    END the program.

ELSE:
    Display "Invalid choice."
    Return to the main menu.

Repeat the menu until the user chooses "Exit."

END

Computational Thinking Used

Decomposition: The problem is divided into smaller tasks such as adding, viewing, and completing school requirements.

Pattern Recognition: Each school task has similar information, such as a subject, task name, deadline, and status.

Abstraction: The program only stores information needed to organize the student's tasks.

Algorithm Design: The program follows a step-by-step process based on the user's selected menu option.

