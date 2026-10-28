# Section A [read me]

# Student Grade Programme

# Overviews

this programme allows you to:
-	be able to input students grades, their names and subjects
-	-the key to basic input operations through the use of scalar objects such as integer floats and loops
-	calculate and output the classes average and total grades.
-	Create basic validation.
-	Show a formatted class report

 # Attributes

-Ask to enter the student's name
-	For each student, it prompts each student’s name and grade
-	Has lists to store the student’s data for later
-	Confirms that every grade:
    Should be numeral
    Should be amongst 0 and 100 [inclusive]
-   compute all students total and their averages of all the grades
-   outputs a class report which displays the grade of students and how it differentiates to the class average
  
# Application

select the programme and run it in the terminal

the output would display the “how many students are in the class?”

From here you input the number of the students, their names, their grades the programme will prompt you to enter a numeric value. If you put a 
negative value the programme will prompt you to enter a numeric value same applies to entering a letter 
after entering the students and their grades the terminal should show you the class report for example;

How many students are in the class? 3

========== CLASS REPORT ==========
Total students : 3
Total grades   : 160.00
Class average  : 53.33
----------------------------------
Amy             Grade:  30.00   (below average)
Layla           Grade:  50.00   (below average)
Jayden          Grade:  80.00   (above average)
==================================

# Input regulations

- the grade should be in positive value from zero to 100
- The number of students should be a positive value
- The name of the student should be any letter or can be any letter
- Do not leave it in blank

# Contributions

- Feel free to add any contributions to the program at Editing bida25-052-python-read-me/README.md at main · nkepuoratile-dev/bida25-052-python-read-me

# Installation 
- Python 2026.6

# Contact
- Name: Oratile Angel Nkepu
- Email: bida25-052@thuto.bac.ac.bw

# Section B

# Overview 

- This programme allows users to:
- Add multiple subjects 
- It contains least which stores the students data for later
- It has tuples Which are subjects = ( ‘Maths’, ‘English’, ‘science’)
- It creates a student summary table which has student names, subject, averages, overall class averages and class average
- Compute the highest and lowest grade for every subject  in the class

# Attributes

- Ensures that every grade should be numeral and should be amongst 0 and 100 [inclusive].
- Make sure that the number of students should be a positive whole number
- Entries which does not fall in the usage rules they are rejected with a clear message and ask the user to prompt again.
- If a student name is left empty it falls back
- It computes all the students averages, overall class average and calculate the highest and lowest grade for every subject in the class
- It prints a student summary table which is displayed or aligned starting by showing the students , subjects [math , English, size] and average to show me class highest and lowest grades for every subject

# Application

- Select the programme and run it in the terminal.
- The output will display “How many students are in the class”, from here you input the number of students, their names, their grades [if you input a negative value the programme will prompt you to enter a numeric value which is positive same applies to entering a letter] for example;

How many students are in the class? 5

--- Student 1 of 5 ---
  Enter student name: Sammy
  Math grade for Sammy (0-100): 50
  English grade for Sammy (0-100): 49
  Science grade for Sammy (0-100): 100

--- Student 2 of 5 ---
  Enter student name: Aole
  Math grade for Aole (0-100): 29
  English grade for Aole (0-100): 10
  Science grade for Aole (0-100): 18

--- Student 3 of 5 ---
  Enter student name: Tee
  Math grade for Tee (0-100): 19
  English grade for Tee (0-100): 69
  Science grade for Tee (0-100): 30

--- Student 4 of 5 ---
  Enter student name: Quinton
  Math grade for Quinton (0-100): 12
  English grade for Quinton (0-100): 78
  Science grade for Quinton (0-100): 60

--- Student 5 of 5 ---
  Enter student name: Mumsy
  Math grade for Mumsy (0-100): Willow
    ✗ Invalid input. Please enter a numeric value.
  Math grade for Mumsy (0-100): 20
  English grade for Mumsy (0-100): 10
  Science grade for Mumsy (0-100): 100

=============================================
STUDENT SUMMARY
=============================================
Student       Math  English  Science  Average
---------------------------------------------
Sammy        50.00    49.00   100.00    66.33
Aole         29.00    10.00    18.00    19.00
Tee          19.00    69.00    30.00    39.33
Quinton      12.00    78.00    60.00    50.00
Mumsy        20.00    10.00   100.00    43.33
---------------------------------------------
CLASS AVERAGE                               43.60
=============================================

PER-STUDENT AVERAGES
------------------------------
  Sammy           avg = 66.33
  Aole            avg = 19.00
  Tee             avg = 39.33
  Quinton         avg = 50.00
  Mumsy           avg = 43.33

SUBJECT EXTREMES (across the class)
---------------------------------------------
  Math       Highest:  50.00 (Sammy)   Lowest:  12.00 (Quinton)
  English    Highest:  78.00 (Quinton)   Lowest:  10.00 (Aole)
  Science    Highest: 100.00 (Sammy)   Lowest:  18.00 (Aole)

Overall class average: 43.60

# Input regulations
The number of students should be a positive number
The student's name can be any text but if it is left blank it will fall back to studentN
the grade it should be any numeral value from zero to 100.

# Contributions

- Feel free to add any contributions to the program at Editing bida25-052-python-read-me/README.md at main · nkepuoratile-dev/bida25-052-python-read-me

# Installation 
- Python 2026.6

# Contact
- Name: Oratile Angel Nkepu
- Email: bida25-052@thuto.bac.ac.bw

# Section C

#  STUDENT GRADE PROGRAM

# overview

 this programme allows users to:

-interact with the grade book through dictionaries and an interactive menu of 7 alternatives

# Attributes

- the menu has a an interactive loop which contains six choices all options which are add students, update students, remove students, search student, view subject grades, add subjects and exit
- Ensures that grades must be between 0 and 100 when adding and updating students
- it displays a selected subject with the student grades, to displace student not found message when the student is missing or not available

# Applications

 Select the programme and run it in the terminal
The output will display the grades menu, from there you select any option you want either to add, update, remove,  search students, view subject grades, add subjects and  exit for example

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 1
Enter student name: Amy
Student added.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 2
Enter student name: Lilly
Student not found.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 1
Enter student name: Lilly
Student added.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 1
Enter student name: Wendy
Student added.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 6
Enter new subject name: Science
Subject added.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 6
Enter new subject name: Maths
Subject added.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 6
Enter new subject name: Setswana
Subject added.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 2
Enter student name: Lilly
Enter new Science grade: 34
Enter new Maths grade: 45
Enter new Setswana grade: 67
Student updated.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 2
Enter student name: Amy
Enter new Science grade: 29
Enter new Maths grade: 45
Enter new Setswana grade: 78
Student updated.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 2
Enter student name: Wendy
Enter new Science grade: 23 
Enter new Maths grade: 56
Enter new Setswana grade: 78
Student updated.

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 5
Enter subject name: Setswana

Grades for Setswana
Amy : 78.0
Lilly : 67.0
Wendy : 78.0

===== GRADEBOOK MENU =====
1. Add Student
2. Update Student
3. Remove Student
4. Search Student
5. View Subject Grades
6. Add Subject
7. Exit
Choose option: 5
Enter subject name: Science

Grades for Science
Amy : 29.0
Lilly : 34.0
Wendy : 23.0

# Code architecture

students{}
Subjects{}
While true loop
Option handlers for example If, else and elif

# Constraints
names which are the same but has different format are treated as different students for example Sam and sam.

# Contributions

- Feel free to add any contributions to the program at Editing bida25-052-python-read-me/README.md at main · nkepuoratile-dev/bida25-052-python-read-me

# Installation 
- Python 2026.6

# Contact
- Name: Oratile Angel Nkepu
- Email: bida25-052@thuto.bac.ac.b

# Section D 

# Overview

This programme allows users to:

- Be able to break down the programme into smaller oh manageable functions [modularization with functions].
- This functions include adding students, adding grades, calculating averages, adding subjects, updating grades and displaying details

# Attributes

- The programme should add student and prevent from entering duplicate
- It should add grades to a student who is existing
- It should also calculate the  students average and should not return nothing if the student does not exist
- It should output the student name, grades and averages
- show all the students with their grades and averages
- should be able to locate a student and update a new grade
- should have a menu which is interactive with seven options
- handles errors with try or Expect value error
- the grades should be numeral and between zero and 100 inclusive
- should not accept any existing students
- show polite messages for students missing and empty grade book

# Application

- Select the programme and run item the terminal. The output would display an interactive menu loop. From there you choose an option from which you want to accomplish a task. For example adding students, adding grades, display students display summary search and update and exit:


GRADEBOOK MENU
1. Add Student
2. Add Grade
3. Display Student
4. Display Summary
5. Search and Update
6. Exit
Choose an option: 1
Enter student name: Amy
Amy added successfully.

GRADEBOOK MENU
1. Add Student
2. Add Grade
3. Display Student
4. Display Summary
5. Search and Update
6. Exit
Choose an option: 2
Enter student name: Amy
Enter grade: 100
Grade added successfully.

GRADEBOOK MENU
1. Add Student
2. Add Grade
3. Display Student
4. Display Summary
5. Search and Update
6. Exit
Choose an option: 3
Enter student name: Amy

Student Details
Name: Amy
Grades: [100.0]
Average: 100.0

GRADEBOOK MENU
1. Add Student
2. Add Grade
3. Display Student
4. Display Summary
5. Search and Update
6. Exit
Choose an option: 4

Student Summary
Amy: [100.0] | Average = 100.00

GRADEBOOK MENU
1. Add Student
2. Add Grade
3. Display Student
4. Display Summary
5. Search and Update
6. Exit
Choose an option: 5
Enter student name to update: Amy
Enter new grade: 45
Grade updated successfully.
Functions
add_students()
add_grades()
calculate_averages()
display_summary()
search_and_update

# Constraints
If names of students are entered with to different formats but they are the same they will be considered different oh considered as two students for example Amy and amy
if you enter a duplicate student name it will be rejected 
with the add_students () she does not reject blank names as compared to other sections above

# Contributions

- Feel free to add any contributions to the program at Editing bida25-052-python-read-me/README.md at main · nkepuoratile-dev/bida25-052-python-read-me

# Installation 
- Python 2026.6

# Contact
- Name: Oratile Angel Nkepu
- Email: bida25-052@thuto.bac.ac.bw


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
