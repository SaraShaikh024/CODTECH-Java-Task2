# CODTECH-Java-Task2

**Name:** Sara Ayaz Shaikh

**Company:** CODTECH IT SOLUTIONS

**ID:** CT08DS6500

**Domain:** Java Programming

**Duration:** August to September 2024

**Mentor:** Neela Santosh Kumar

**Project Overview**
**Objective:** The StudentGradeTracker is a console-based Java application designed to help users manage and track grades for different subjects associated with individual students. The application allows users to add grades, display grades, calculate averages, and provides a basic text-based menu for interaction.

**Features:**

**1.	Add Grade:**
o	Users can enter a student’s name, a subject, and the corresponding grade. The grade is stored in a list associated with the student.

**2.	Display Grades:**
o	Users can retrieve and view all grades for a specified student.

**3.	Calculate Average:**
o	Users can calculate and display the average grade for a specified student. The application also determines the letter grade based on the average.

**4.	Exit:**
o	Allows users to exit the application.

**Functionality and Flow:**

**1.	User Interaction:**

o	The application presents a menu to the user with options to add grades, display grades, calculate averages, or exit.

o	User input is handled through a Scanner object to read commands and grade data.

**2.	Grade Management:**

o	Grades are managed using a HashMap where each key is a student’s name and each value is an ArrayList of SubjectGrade objects.

o	This structure allows for efficient retrieval and management of grades associated with each student.

**3.	Input Validation:**

o	The application includes input validation to ensure that grades are within a valid range (0 to 100) and handles non-numeric input gracefully.

o	The integer input for menu choices is also validated to handle invalid entries.

**4.	Calculations and Output:**

o	The average grade is computed by summing all grades for a student and dividing by the number of subjects.

o	The average is then converted into a letter grade according to standard grading thresholds.

**Enhancements and Improvements:**

**1.	Student Management:** The application supports tracking grades for multiple students, providing a more comprehensive grade management system.

**2.	Error Handling:** Improved user input handling ensures robustness against invalid entries.

**3.	Extensibility:** The application can be extended further to include features like data persistence, more detailed subject management, or a graphical user interface.

This overview encapsulates the core functionality, structure, and features of the StudentGradeTracker application. It’s designed to be a simple yet effective tool for managing and tracking student grades in a console-based environment.

