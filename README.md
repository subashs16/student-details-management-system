Student details management system
Overview:
The Student Details Management System is a simple command-line application that allows users to manage student records.
This application provides functionality to add, view, update, and delete student information.

Features:
Add Student: Add a new student with ID, name, age, and grade.
View Students: Display all students currently in the system.
Update Student: Update details (name, age, grade) of an existing student.
Delete Student: Remove a student from the system by their ID.

Classes:
'Student'
This class represents a student and has the following attributes:

'student_id': A unique identifier for the student.
'name': The student's name.
'age': The student's age.
'grade': The student's grade.

Constructor:
def __init__(self, student_id, name, age, grade):

'StudentManagementSystem'
This class manages a collection of students and provides methods to manipulate student records.

Constructor:

python
Copy code
def __init__(self):
Initializes an empty dictionary to store students.
Methods:

add_student(student): Adds a new student to the system. Prints a message if the student ID already exists.
view_students(): Displays all students in the system. Prints a message if no students are found.
update_student(student_id, name=None, age=None, grade=None): Updates the details of an existing student. Prints a message if the student ID is not found.
delete_student(student_id): Deletes a student by ID. Prints a message if the student ID is not found.
Usage
Run the main function to start the application. The application will display a menu with the following options:

Add student: Enter student details to add a new student.
View students: Display a list of all students.
Update student: Enter student ID and new details to update an existing student's information.
Delete student: Enter student ID to remove a student from the system.
Exit: Exit the application.
Example
To run the application, execute the script:

bash
Copy code
python student_management_system.py
Follow the on-screen prompts to interact with the system.

Code Structure
Student: Contains the attributes and constructor for a student.
StudentManagementSystem: Manages student records with methods for adding, viewing, updating, and deleting students.
main(): Provides the command-line interface for interacting with the StudentManagementSystem.
Requirements
Python 3.x
