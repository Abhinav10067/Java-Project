Student Habit Tracker

A simple console-based Java application to help students build and track daily habits. Add habits, mark them as completed, view your habit list, and generate a quick progress report — all from a menu-driven command-line interface.

Features
Add Habit – Create a new habit to track
Delete Habit – Remove a habit you no longer want to track
View Habits – List all habits you're currently tracking
Mark Habit Completed – Mark a habit as done for the day
View Report – See a summary report of your habit progress
Exit – Close the application
Project Structure
Java-Project/
├── HabitTrackerMain.java   # Entry point with the interactive menu
├── Habit.java              # Habit model class
├── HabitService.java       # Business logic for managing habits (add/delete/view/mark complete)
├── ReportService.java      # Generates and displays the habit progress report
└── README.md
Requirements
Java Development Kit (JDK) 8 or higher
Getting Started
1. Clone the repository
bash
git clone https://github.com/Abhinav10067/Java-Project.git
cd Java-Project
2. Compile the project
bash
javac *.java
3. Run the application
bash
java HabitTrackerMain
Usage

Once running, you'll see a menu like this:

===== Habit Tracker =====
1. Add Habit
2. Delete Habit
3. View Habits
4. Mark Habit Completed
5. View Report
6. Exit
Enter your choice:

Enter the number corresponding to the action you want to perform, and follow the on-screen prompts (e.g., entering a habit name).

Example
Enter your choice: 1
Enter habit name: Read for 30 minutes

Enter your choice: 4
Enter habit name to mark complete: Read for 30 minutes

Enter your choice: 5
Tech Stack
Language: Java
Interface: Command-line (CLI)


