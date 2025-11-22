# java-lab-assignment-1
A simple Java Student Record System that uses ArrayList to store student data. Users can add student details through console input and view all stored records. Each student has name, roll number, course, marks, and a grade calculated from marks. Provides a menu-driven interface for operations.

🧾 Student Record Management System (Java)

📘 Project Overview

The Student Record Management System is a simple Java console-based application designed to store and manage student details.
It demonstrates the concepts of Object-Oriented Programming (OOP) such as classes, inheritance, methods, and encapsulation.

This project allows users to:

Add new student records
Display all stored student records
Exit the program safely
⚙️ Technologies Used

Language: Java (JDK 24 or higher)
Concepts Covered:
Inheritance
Encapsulation
Object creation
User input handling using Scanner
Dynamic data storage using ArrayList
🧩 Class Structure

1. Person (Parent Class)

Attributes:
name — stores student’s name.
Purpose: Acts as a base class for inheritance.
2. Student (Child Class)

Inherits: Person
Attributes:
rollNo — student’s roll number
course — course name
marks — total marks
grade — grade (calculated automatically)
Methods:
inputDetails() — accepts user input for student details.
calculateGrade() — assigns grade based on marks.
displayDetails() — prints student information.
3. StudentRecordSystem (Main Class)

Functionality:
Contains the main() method that provides a simple menu-driven interface for users.
💡 Features

✅ Add new students with complete details
✅ Automatically calculate grades based on marks
✅ Display all student records in a formatted manner
✅ Simple and interactive command-line interface

📊 Grade Calculation Logic

Marks Range	Grade
90 - 100	A
75 - 89	B
50 - 74	C
Below 50	D
1️⃣ Save the file

Save the code as:
