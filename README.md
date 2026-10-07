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




