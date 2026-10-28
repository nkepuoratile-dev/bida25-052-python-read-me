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

