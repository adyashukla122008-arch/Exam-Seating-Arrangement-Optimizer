Exam Seating Arrangement Optimizer

A simple Python-based console application developed as a first-semester college project.

The project is designed to manage student roll numbers, configure examination rooms, generate seating arrangements, search for student seats, and check room capacity.

About the Project

Managing examination seating arrangements manually can become difficult when there are multiple students and rooms.

This project provides a basic way to manage the process using Python. Users can enter student roll numbers, set the number of rooms and seats available, and generate a seating arrangement based on the available capacity.

The project was created to practice basic Python programming concepts and apply them to a simple real-world problem.

Features
Student Data

Add multiple student roll numbers

View the list of students

Clear all student data

Exam and Room Setup

Enter the number of examination rooms

Enter the number of seats available in each room

Calculate the total seating capacity

Seating Arrangement

Generate a seating arrangement automatically

Check whether enough seats are available

Display the arrangement room by room

Student Seat Search

Search for a student using their roll number

Display the assigned room number

Display the assigned seat number

Room Capacity

Display the total number of seats

Display the number of occupied seats

Display the number of available seats

Technologies Used

Python 3

Python Lists

for loops

while loops

Conditional statements

User input and output

Basic searching and indexing

Basic arithmetic operations

How the Program Works

The program uses a menu-driven interface.

========== EXAM SEATING ARRANGEMENT OPTIMIZER ==========

1. Student Data
2. Exam/Room Setup
3. Generate Seating Arrangement
4. View Seating Arrangement
5. Search Student Seat
6. Check Room Capacity
7. Exit


The basic workflow is:

Add Students
     |
     v
Set Up Rooms
     |
     v
Check Seating Capacity
     |
     v
Generate Arrangement
     |
     +------------------+
     |                  |
     v                  v
View Arrangement   Search Student
     |
     v
Check Room Capacity
     |
     v
    Exit

Example

Suppose the room setup is:

Number of Rooms: 2
Seats Per Room: 5
Number of Students: 8


The total capacity is:

2 × 5 = 10 seats


Therefore:

Occupied Seats: 8
Available Seats: 2


A generated arrangement may look like:

========== SEATING ARRANGEMENT ==========

----- ROOM 1 -----
Seat 1 : 101
Seat 2 : 103
Seat 3 : 105
Seat 4 : 107
Seat 5 : 102

----- ROOM 2 -----
Seat 1 : 104
Seat 2 : 106
Seat 3 : 108


A student can also be searched using their roll number to find their assigned room and seat.

How to Run
Requirements

Python 3.x

A Python IDE or text editor

Check your Python installation:

python --version

Run the Project

Download the project files and open the project folder.

Run the Python file:

python main.py


If your Python file has a different name, replace main.py with the appropriate filename.

Project Structure
exam-seating-arrangement-optimizer/
|
├── main.py
├── README.md
└── .gitignore

Project Objective

The main objective of this project is to use basic Python programming concepts to solve a simple problem related to examination seating arrangements.

The project was developed as part of my first-semester learning to gain practical experience with Python and understand how programming can be applied to real-world problems.

What I Learned

While developing this project, I practiced:

Working with Python lists

Using for and while loops

Using conditional statements

Taking input from users

Searching data in lists

Using list indexing

Performing basic calculations

Creating a menu-driven program

Handling different program conditions

Breaking a problem into smaller programming steps

Limitations

The current version of the project has some limitations:

Student data is not permanently stored.

Data is lost when the program is closed.

Duplicate roll numbers are not currently checked.

Input validation is limited.

Student names are not stored.

Seating arrangements are not randomized.

There is no database integration.

The application currently runs through the terminal.

Future Improvements

As I continue learning Python and other technologies, I would like to improve this project by adding:

Student names along with roll numbers

Duplicate roll number detection

Better input validation

Randomized seating arrangements

File-based data storage

Database integration

A graphical user interface

Printable seating arrangements

Better error handling

Project Status

Status: Completed — Initial Version

This is one of my early programming projects and is part of my learning journey as a first-semester college student.

I plan to improve the project as I learn more about Python, data structures, databases, and software development.

Author

[ADYA]

B.Tech in Computer Science and Engineering (AI & ML)

School of Computing and Artificial Intelligence (SCAI)

VIT Bhopal University
