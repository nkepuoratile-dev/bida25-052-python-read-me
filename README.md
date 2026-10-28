
# SECTION E

# Overview

This program allows users to:

- Model the grade book into two classes:
   - Student- it contains a single student in which though they will have their name, grades, add grade, calculate average and display details.
   - Grade book- which contains multiple student and manages them through add, remove, search and display students sort student by their averages.

# Attributes

- Has two classes which are gradebook and student
- Every student has their own grade and  list
- the programme has great validation which means that the programme does not allow the grade to be less than 0 or more than 100.
- The programme also has case sensitive search
- the programme also sort by averages
- includes an interactive menu with 7 alternatives
- has error handling

# Application

Select the programme and run it in the terminal the output will display an interactive menu with seven alternatives in which you would choose especially from 1

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 1
Enter student name: Masego
Student added successfully.

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: Masego
Enter grade: 78

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 5

Students Sorted by Average
Masego: 78.00

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: Masego
Enter grade: 88

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 5

Students Sorted by Average
Masego: 83.00

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: 56
Student not found.

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 5

Students Sorted by Average
Masego: 83.00

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 1
Enter student name: Mavis
Student added successfully.

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: 78
Student not found.

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: Mavis
Enter grade: 99

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 4

Student Details
Name: Masego
Grades: [78.0, 88.0]
Average: 83.0

Student Details
Name: Mavis
Grades: [99.0]
Average: 99.0

# Programme architecture

Error handling

# Class overview

Student class
name
Grades
Add_grade
Calculate_average
Display_details 

Grade book class
Students
Add_student
remove_students
search_student
Display_all_students
Sort_by_average

# Constraints
- Has case sensitive search
- It accepts empty names of student
the function add_student is not case sensitive which means that if you add duplicate names it will consider them as two different students

# Contributions

- Feel free to add any contributions to the program at Editing bida25-052-python-read-me/README.md at main · nkepuoratile-dev/bida25-052-python-read-me

# Installation 
- Python 2026.6

# Contact
- Name: Oratile Angel Nkepu
- Email: bida25-052@thuto.bac.ac.bw


# SECTION F 

# Overview

- This programme deals with custom exception handling which means that with object-created design from the section above which is section E, the programme does not return none or error messages but brings out a dedicated reception type which callers will see and handle them.

These exceptions include:

studentNotFoundException
 This is whereby the student is not found or cannot be found in the grade book

InvalidGradeError
 This is whereby an invalid grade is entered, an invalid grade could be a non numeral grade update which is less than 0 or more than 100.

# Attributes

- contains two classes which are gradebook and class
- there's an interactive menu with 7 alternatives
- contain search and removal case sensitives
- Also sort by average
- Has great validation
- contains conception classes which are studentNotFoundException and InvalidGradeError

# Application

- Select the programme and run it in the terminal. The output in the terminal will display an interactive manual with 7 alternatives which you would choose from option one to input your data.

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 1
Enter student name: Mavis
Student added successfully.

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: Mavis
Enter grade: 67

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 1
Enter student name: Lolly
Student added successfully.

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: Lolly
Enter grade: 34

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: Lolly
Enter grade: 89

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: Mavis
Enter grade: 40

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 3
Enter student name: Lolly

Student Details
Name: Lolly
Grades: [34.0, 89.0]
Average: 61.5

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 4

Student Details
Name: Mavis
Grades: [67.0, 40.0]
Average: 53.5

Student Details
Name: Lolly
Grades: [34.0, 89.0]
Average: 61.5

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 5

Students Sorted by Average
Lolly: 61.50
Mavis: 53.50

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 6
Enter student name to remove: Lolly
Student removed.

GRADEBOOK SYSTEM
1. Add Student
2. Add Grade
3. Search Student
4. Display All Students
5. Sort by Average
6. Remove Student
7. Exit
Enter choice: 2
Enter student name: 34
Traceback (most recent call last):
  File "C:\Users\user\PycharmProjects\Section C\SECTION F.py", line 101, in <module>
    student = gradebook.search_student(name)
  File "C:\Users\user\PycharmProjects\Section C\SECTION F.py", line 58, in search_student
    raise StudentNotFoundException("Student not found")
StudentNotFoundException: Student not found

# Programme Architecture
studentNotFoundException
 This is whereby the student is not found or cannot be found in the grade book
InvalidGradeError
 This is whereby an invalid grade is entered, an invalid grade could be a non numeral grade update which is less than 0 or more than 100.

Class diagram
Student class
name
Grades
Add_grade
Calculate_average
Display_details 

Grade book class
Students
Add_student
remove_students
search_student
Display_all_students
Sort_by_average

Constraints
It accepts empty names of student
the function add_student is not case sensitive which means that if you add duplicate names it will consider them as two different students
If you enter a student which is not found in the grade book or the class you will out we'll encounter an error this called studentNotFoundException
if you enter an invalid grade which is a grade is less than 0 or more than 100 or not a numeral value you will encounter an error which is called InvalidGradeError.

# Contributions
- Feel free to add any contributions to the program at Editing bida25-052-python-read-me/README.md at main · nkepuoratile-dev/bida25-052-python-read-me

# Installation 
- Python 2026.6

# Contact
- Name: Oratile Angel Nkepu
- Email: bida25-052@thuto.bac.ac.bw
