Student Management System (CLI)

A simple command-line Student Management System written in Python. It lets you store student records in memory and manage them through an interactive menu. Built as a beginner project to practice functions, dictionaries, lists, loops, and user input handling.

Features
Add Student: store name, roll number, age, and marks for Math, English, and Science
View Students: list all saved student records
Search Student: look up a student by name
Update Marks: change a student's marks for a subject
Delete Student: remove a student record by name
Calculate Average: compute a student's average marks across the three subjects
Exit: quit the program cleanly
Tech Stack
Python 3
No external libraries required
Runs in Google Colab, Jupyter Notebook, or any Python environment
Getting Started
Option 1: Google Colab / Jupyter
Open Student_Project.ipynb in Google Colab or Jupyter Notebook.
Run the cell.
Follow the on-screen menu.
Option 2: Run locally
bash
git clone https://github.com/<your-username>/student-management-system-cli.git
cd student-management-system-cli
jupyter notebook Student_Project.ipynb
Usage

When you run the program, you'll see this menu:

----------MAIN MENU-------------
1. Add Student
2. View Student
3. Search Student
4. Update Marks
5. Delete Student
6. Calculate Average
7. Exit

Enter the number of the action you want and follow the prompts.

Example student record
python
{
    'name': 'ahrar',
    'roll': 1,
    'age': 18,
    'math': 85,
    'english': 78,
    'science': 90
}
Project Structure
student-management-system-cli/
├── Student_Project.ipynb   # Main project notebook
└── README.md               # Project documentation
Known Issues & Roadmap

This project is a work in progress. Planned fixes and improvements:

 Fix Update Marks so it finds a student and updates their stored marks
 Fix Calculate Average so it works per student
 Fix Delete Student so the "does not exist" message only shows when no match is found
 Correct the menu call for updating marks (function name mismatch)
 Remove the duplicate search_stu() definition
 Add input validation (e.g., handle non-numeric input and marks outside 0-100)
 Save data to a file (JSON/CSV) so records persist between runs
 Prevent duplicate roll numbers
Learning Goals
Working with lists and dictionaries
Writing and organizing functions
Using loops and conditionals for menu-driven programs
Handling user input
