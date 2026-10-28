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
- Email: bida25-052@thuto.bac.ac.bw

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

