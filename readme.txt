Student Grade Calculator
A simple C++ program that calculates a student's grade based on their marks in three subjects.

Overview
This program defines a struct students to store student data, including ID, name, marks in three subjects, and grade. It then prompts the user to input student data, calculates the average marks, and assigns a grade based on the average.

Features
- Calculates average marks
- Assigns grade based on average marks (A for 90%+, B for 80-89%, C for below 80%)
- Validates user input for marks (ensures marks do not exceed 100)

Requirements
- C++ compiler (e.g., GCC)
- Standard C++ libraries (e.g., iostream)

Usage
1. Compile the program using a C++ compiler (e.g., g++ student_grade_calculator.cpp -o student_grade_calculator)
2. Run the program (e.g., ./student_grade_calculator)
3. Follow the prompts to input student data

Notes
- This program uses a simple struct to store student data. For larger applications, consider using more advanced data structures or classes.
- Error handling is minimal in this program. Consider adding checks for invalid user input or other potential errors.