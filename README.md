# gradebook_analyzer
📝 Project Description
GradeBook Analyzer CLI is a Python-based tool that helps teachers analyze student performance after class tests. Instead of using spreadsheets, this script collects student names and marks manually, calculates statistics, assigns grades, and displays results in a clean tabular format.

🎯 Learning Objectives
- Input and store student data using dictionaries
- Calculate average, median, max, and min scores
- Assign letter grades using control statements
- Filter pass/fail students using list comprehensions
- Display results in a formatted table
- Use modular functions and loops for clean code

📂 Project Structure
gradebook_analyzer/
│
└── gradebook.py       # Main script with all logic

🚀 How to Run
- Open gradebook.py in your Python IDE or terminal.
- Enter the number of students.
- Input each student's name and marks.
- View statistics, grades, pass/fail summary, and results table.

✅ Features
- Manual input for student names and marks
- Grade assignment using if–elif–else logic
- Grade distribution count
- Pass/fail filtering using list comprehension
- Formatted output table
- Modular code with comments

📌 Sample Output 

----- !! Welcome to GradeBook Analyzer CLI by SUHANI YADAV !! -----

Enter number of students: 5
Enter name of student 1: suhani yadav
Enter marks for suhani yadav: 100
Enter name of student 2: prabhat bhatia
Enter marks for prabhat bhatia: 29
Enter name of student 3: aayan
Enter marks for aayan: 45
Enter name of student 4: muskaan
Enter marks for muskaan: 89
Enter name of student 5: aradhya
Enter marks for aradhya: 66

Stored Marks:
{'suhani yadav': 100.0, 'prabhat bhatia': 29.0, 'aayan': 45.0, 'muskaan': 89.0, 'aradhya': 66.0}

Statistics:
Average Marks: 65.80
Median Marks: 66.00
Highest Marks: 100.0
Lowest Marks: 29.0

Grade Distribution:
A: 1 student(s)
B: 1 student(s)
C: 0 student(s)
D: 1 student(s)
F: 2 student(s)
{'suhani yadav': 'A', 'prabhat bhatia': 'F', 'aayan': 'F', 'muskaan': 'B', 'aradhya': 'D'}

Pass/Fail Summary:
Passed (4): suhani yadav, aayan, muskaan, aradhya
Failed (1): prabhat bhatia

Final Results Table:
Name           Marks     Grade
-------------------------------
suhani yadav   100.00    A
prabhat bhatia 29.00     F
aayan          45.00     F
muskaan        89.00     B
aradhya        66.00     D


Author & Course
Suhani Yadav
2501410032
B.Tech CSE Cyber Security(First Semester)
5th November 2025
Programming With Python - Lab Assignment 2



