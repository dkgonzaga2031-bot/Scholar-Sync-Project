#  ScholarSync: Student Task & Study Load Analyzer (PROJECT PROPOSAL)

##  About the Project

ScholarSync is a command-line study tracker designed to help students manage their academic workload. It records school tasks, deadlines, difficulty levels, and study hours using a JSON file.

By calculating descriptive statistics and generating workload insights, ScholarSync helps students identify demanding subjects, monitor their progress, and improve their study habits.

##  Problem Statement

Students often handle multiple deadlines across different subjects without properly tracking their tasks and study hours. Relying on memory can lead to last-minute cramming, poor time management, and uneven study habits.

ScholarSync addresses this problem by organizing academic tasks and comparing estimated study hours with actual time spent. This allows students to better understand and balance their weekly workload.

##  Features

ScholarSync offers the following features:

- *Create Tasks* – Add tasks with a subject, title, difficulty level (1–5), due date, estimated hours, and actual hours.
- *View Tasks* – Display all recorded tasks, filter them by subject, and sort them by due date or status.
- *Update Tasks* – Edit task details, update due dates, mark tasks as completed, and record actual study hours.
- *Delete Tasks* – Remove tasks using their unique IDs after a confirmation prompt.
- *Study Analytics* – Generate statistics about academic workload and study habits.

###  Analytics and Insights

The program calculates:
- Total number of tasks
- Task completion rate
- Total and average study hours
- Subject workload distribution
- Average task difficulty per subject
- Estimated versus actual study hours
- Workload and overload alerts

##  Technologies Used

- *Python* – Main programming language
- *JSON* – Persistent data storage
- *GitHub* – Project collaboration and version control

##  Data Storage

ScholarSync uses a JSON file named tasks_data.json to store academic task records.

Each task contains the following information:

- Task ID
- Subject
- Task title
- Difficulty level
- Due date
- Estimated study hours
- Actual study hours
- Completion status

The JSON format allows the program to save and retrieve records, making it possible to track academic progress over multiple weeks.

## Program Menu

Users can interact with ScholarSync through the following menu:

```text

==================================================
     SCHOLARSYNC: STUDENT STUDY LOAD ANALYZER
==================================================
[1] Add New Task
[2] View All Tasks / Filter by Subject
[3] Update Task Status / Log Actual Hours
[4] Delete a Task
[5] View Study Analytics & Descriptive Statistics
[6] Save & Exit
--------------------------------------------------
Enter your choice (1-6):
```
