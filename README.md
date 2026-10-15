# bida25-052-python-read-me

# Student Grade Program

# Step 1: Ask how many students are in the class
number_of_students = int(input("Enter the number of students in the class: "))

# Lists to store the names and grades
names = []
grades = []

# Step 2: Loop through each student
for i in range(number_of_students):
    print("\n--- Student", i + 1, "---")

    # Get the student's name
    name = input("Enter student name: ")

    # Get the grade, and keep asking until it is valid (0 to 100)
    grade = float(input("Enter grade (0-100): "))
    while grade < 0 or grade > 100:
        print("Invalid grade! Grade must be between 0 and 100.")
        grade = float(input("Enter grade (0-100): "))

    # Save the name and grade
    names.append(name)
    grades.append(grade)

# Step 3: Calculate total and average
total = 0
for grade in grades:
    total = total + grade

average = total / number_of_students

# Step 4: Display the results
print("\n===== CLASS RESULTS =====")
print("Total of all grades:", total)
print("Class average:", round(average, 2))

print("\n===== STUDENT GRADES =====")
for i in range(number_of_students):
    print(names[i], "- Grade:", grades[i], "| Class Average:", round(average, 2))

    subjects = ["Math", "English", "Science"]
students = []

# ----- Get the data -----
number = int(input("How many students? "))

for i in range(number):
    name = input("Enter student name: ")

    grades = []
    for subject in subjects:
        grade = float(input("Enter " + subject + " grade: "))
        grades.append(grade)

    student = (name, grades)    # tuple: name + list of grades
    students.append(student)

# ----- Summary table -----
print("\nName\tMath\tEnglish\tScience\tAverage")

for student in students:
    name = student[0]
    grades = student[1]
    average = sum(grades) / len(grades)
    print(name, grades[0], grades[1], grades[2], round(average, 2), sep="\t")

# ----- Highest and lowest per subject -----
print()
for i in range(len(subjects)):
    subject_grades = []
    for student in students:
        subject_grades.append(student[1][i])

    print(max(subject_grades), min(subject_grades))

# SECTION C: USING DICTIONARIES FOR STUDENT MANAGEMENT
from os import name

#Dictionary where
#the parent dictionary: students name
#the child dictionary: (subject: list of grades)

students={

    "Clinton":{
        "Math":[90,86,56],
            "Science":[87,67,78],
          "English":[78,68,90],
                },

    "John": {
        "Math": [80, 76, 46],
        "Science": [77, 87, 98],
        "English": [98, 78, 100],
    },

    "Smith": {
        "Math": [70, 66, 86],
        "Science": [97, 67, 58],
        "English": [88, 100, 80],
    }
        }

#student management

def add_student(names):
    if name in students:
        print("Student preexisting")
    else:
        students[name]={}
        print("Student added.")


def update_grades(name,subject,grades):
    if name not in students:
        print("Student not found.")
        return

    if subject in students [name]:
            students [name][subject] += grades #append new grades

    else:
        students[name][subject]= grades
        print("Grades added.")

def remove_student(name):
    if name in students:
        print("Student deleted.")
    else:
        print("Student not found.")

#2 subject-specific grades

def view_subject(subject):
    print("f/nGrades for subject, {subject}:")
    for name in students [subject]:
        if subject in students [name]:
            grades = students [name][subject]
            avg= sum(grades) / len(grades)
            print("f {name}: {grades} | Avg: {avg:.2f}" )

#3 Search Student

def search_student(name):
    if name not in students:
        print("Student not found.")
        return

print(f"\nReport for [name]")
all_grades= []

for subject in students[name]:
    grades = students[name][subject]
    avg= sum(grades) / len(grades)
    print("f {name}: {grades} | Avg: {avg:.2f}" )
    all_grades +=grades

if all_grades:
    print(f"Overall Grades: { sum(all_grades)/ len(all_grades)} 2f")


def menu():
    while True:

      print("\n.Add student")
      print("2. Update grades")
      print("3. Remove student")
      print("4. View student grades")
      print("5. Search student")
      print("6. Show all students")
      print("7. Exit")

choice = int(input("Enter your choice: "))

if choice == 1:
    add_student(input("Enter student name: "))

elif choice == 2:
    name=input("Enter student name: ")
    subject = input("Enter subject: ")
    grades = input("Enter grades: ")
    update_grades(name, subject, grades)

elif choice == 3:
    remove_student(input("Enter student name: "))

elif choice == 4:
    view_subject(input("Enter subject: "))

elif choice == 5:
    search_student(input("Enter student name: "))

elif choice == 6:
    for name in students:
        print(name)

elif choice == 7:
    print("Goodbye")
    "break"

else:
    print("Invalid choice")

#run

menu()

SECTION D
Overview
This program allows a user to:

Add and remove students

Record and update grades per subject

View grades for a specific subject across all students

Search for a student and see their full report

View a summary of all students with overall averages

The code is modularized into small, reusable functions, with built-in validation and error handling.

Data Structure
Student data is stored in a single dictionary called students:

python
students = {
    "student_name": {
        "subject_name": [grade1, grade2, ...],
        ...
    },
    ...
}
Key → student name (string)

Value → another dictionary mapping subject names to lists of grades (floats)

Example:

python
{
    "Alice": {
        "Math": [85.0, 90.5],
        "Science": [78.0]
    },
    "Bob": {
        "Math": [70.0, 65.5]
    }
}
Features
#	Feature	Description
1	Add student	Adds a new student by name
2	Update grades	Adds or appends grades for a student in a subject
3	Remove student	Deletes a student and all their data
4	View grades for a subject	Shows every student's grades and average for a subject
5	Search student	Displays a full report (per-subject + overall average)
6	Show all students	Lists all students in the system
7	Search & update student	Combines search and grade update in one flow
8	Show student summary	Displays every student with subject count and overall average
9	Exit	Closes the program
Functions Reference
Helper Functions
Function	Purpose
calculate_average(grades)	Returns the average of a list of grades, or None if the list is empty
get_student(name)	Returns the student's data dictionary, or None if not found
parse_grades(grades_input)	Converts a space-separated string into a list of floats; raises ValueError for invalid input
Core Feature Functions
Function	Purpose
add_student()	Adds a new student after validating the name
update_grades()	Adds or appends grades for an existing student
remove_student()	Deletes a student if they exist
view_grades_for_subject()	Displays grades and averages for a subject across all students
search_student()	Displays a full report for one student
search_and_update()	Searches for a student and updates their grades
show_all_students()	Lists all students
show_students_summary()	Displays a summary of every student
Menu Functions
Function	Purpose
print_menu()	Prints the main menu options
main()	Runs the main loop, reads user input, and dispatches to the correct function
Error Handling
The program handles the following error cases gracefully:

Empty student name or subject → rejected with an error message

Duplicate student → warns the user instead of overwriting

Non-numeric grades → caught via try/except and reports the offending token

No grades entered → rejected with an error message

Missing student → reported as "Student not found"

Empty grade lists → calculate_average() returns None to avoid ZeroDivisionError

Example of a caught error:

text
Enter grades separated by spaces: 85 abc 90
Error: 'abc' is not a valid number.
How to Run
Requirements
Python 3.6 or later

No external libraries required

Steps
Save the code to a file, e.g. student_manager.py

Run it from the terminal:

bash
python student_manager.py
Use the numbered menu to interact with the program.

Example Session
text
--- STUDENT MANAGEMENT MENU ---
1. Add student
2. Update grades
...
Enter your choice: 1
Enter student name: Alice
Student 'Alice' added.

Enter your choice: 2
Enter student name: Alice
Enter subject: Math
Enter grades separated by spaces: 85 90.5
Grades added.

Enter your choice: 5
Enter student name: Alice

Report for Alice
Math: [85.0, 90.5] | Avg: 87.75
Overall Average: 87.75
Design Notes
Modularity: Each feature is a separate function, making the code easy to test, extend, and maintain.

Reusability: Helpers like calculate_average() and parse_grades() are used across multiple features.

Validation: Inputs are validated inside functions rather than at the menu level, so each function is safe to call independently.

In-memory only: Data is not persisted to disk. Restarting the program clears all records.

Possible Enhancements
Save/load student data to a file (JSON or CSV)

Add letter-grade conversion (A, B, C, …)

Support editing or deleting individual grade entries

Add sorting/filtering options (e.g., by average, by subject)

Convert to a GUI or web app (e.g., Tkinter, Flask)


