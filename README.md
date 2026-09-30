Exam Seating Arrangement Optimizer

A simple Python-based console application developed as a first-semester college project.

The project is designed to manage student roll numbers, configure examination rooms, generate seating arrangements, search for student seats, and check room capacity.

About the Project

Managing examination seating arrangements manually can become difficult when there are multiple students and rooms.

This project provides a basic solution by allowing the user to enter student details and room information and then generate a seating arrangement based on the available seating capacity.

The project is built using basic Python concepts that I have learned during my first semester.

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
     +----------+----------+
     |                     |
     v                     v
View Arrangement     Search Student
     |
     v
Check Room Capacity

Example

Suppose there are:

Number of Rooms: 2
Seats Per Room: 5
Number of Students: 8


The total capacity is:

2 × 5 = 10 seats


Therefore:

Occupied Seats: 8
Available Seats: 2


The generated arrangement can then be viewed room by room.

For example:

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


A student can also be searched using their roll number to find their room and seat.

How to Run
Requirements

Python 3.x

Git

Check your Python installation:

python --version

Clone the Repository
git clone https://github.com/your-username/exam-seating-arrangement-optimizer.git


Navigate to the project directory:

cd exam-seating-arrangement-optimizer


Run the program:

python main.py


If your Python file has a different name, replace main.py with the appropriate filename.

Project Structure
exam-seating-arrangement-optimizer/
|
├── main.py
├── README.md
└── .gitignore

What I Learned

I developed this project to improve my understanding of Python programming.

Through this project, I practiced:

Working with lists

Using loops

Using conditional statements

Taking input from users

Searching data in lists

Using list indexing

Performing basic calculations

Creating a menu-driven program

Solving a simple real-world problem using programming

Limitations

This is an initial version of the project, so it currently has some limitations:

Student data is not permanently stored

Duplicate roll numbers are not checked

The application runs only in the terminal

Input validation is limited

Seating arrangements are not randomized

There is no database integration

Future Improvements

As I continue learning Python and other technologies, I plan to improve this project by adding:

Student names along with roll numbers

Duplicate roll number detection

Better input validation

Randomized seating arrangements

File-based data storage

Database integration

A graphical user interface

Printable seating arrangement reports

Project Status

Current Status: Completed - Initial Version

This project represents one of my early programming projects and is part of my learning journey as a first-semester college student.

I plan to continue improving it as I learn more about Python, data structures, databases, and software development.

Author

[ADYA]

First Semester College Student

This project was created for learning and educational purposes.
