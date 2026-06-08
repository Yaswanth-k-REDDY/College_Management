College Student Management System

Overview

This project is a simple Python-based College Student Management System designed to demonstrate the practical use of Python Data Structures including:

- Dictionaries
- Lists
- Tuples
- Sets

The system stores multiple class sections and their students, along with student details such as roll numbers and marks.

---

Data Structure Design

The project uses a nested data structure:

Dictionary

Stores class sections.

college = {
    "CSE-A": [...],
    "CSE-B": [...],
    "CSE-C": [...],
    "CSE-D": [...]
}

List

Stores students belonging to a section.

[
    (...),
    (...),
    (...)
]

Tuple

Represents an individual student record.

("Yash", {...})

Dictionary (Inside Tuple)

Stores student attributes.

{
    "roll_no": 101,
    "marks": 95
}

Set

Stores unique subjects offered in the college.

subjects = {"Python", "DBMS", "AI", "Java"}

---

Features

Implemented Features

- Store multiple class sections
- Store student information
- Display all students
- Organize data efficiently using nested structures

Additional Features That Can Be Added

- Add Student
- Delete Student
- Search Student by Name
- Search Student by Roll Number
- Update Marks
- Find Section Topper
- Find Overall College Topper
- Calculate Average Marks
- Display Available Subjects

---

Project Structure

College
│
├── CSE-A
│   ├── Student 1
│   ├── Student 2
│   ├── Student 3
│   └── Student 4
│
├── CSE-B
│
├── CSE-C
│
└── CSE-D

---

Sample Student Record

("Yash", {
    "roll_no": 101,
    "marks": 95
})

---

Learning Outcomes

After completing this project, students will understand:

- Dictionary operations
- List manipulation
- Tuple usage
- Set operations
- Nested data structures
- Data organization techniques
- Basic problem-solving using Python

---

Technologies Used

- Python 3.x

---

Future Enhancements

- Menu-driven interface
- File handling for data persistence
- Student result analysis
- Grade calculation
- Graphical User Interface (GUI)
- Database integration using MySQL or SQLite

---

Author

Developed as a Day 1 Mini Project in the AI Orchestrator Learning Journey to strengthen Python Data Structures fundamentals.