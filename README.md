NAME:SIDDHI JAMDADE
COMPANY:CODTECH IT SOLUTIONS
ID
DOMAIN:JAVA PROGRAMMING
DURATION:DEC TO JAN2024
MENTOR:SRAVANI GOUNI

Project Overview: Student Grades Manager

![Screenshot 2024-12-23 213541](https://github.com/user-attachments/assets/0d98b939-5e13-4999-ad02-626b884f5cb8)


Objective:
The `Student Grades Manager` is a Java-based console application designed to help users input and manage student grades, calculate the average grade, and display performance metrics such as letter grades and GPA.

Key Features:

1. Interactive Menu System:
   - Provides users with a menu-driven interface to perform tasks like adding grades, calculating the average, and displaying overall grade information.

2.Grade Management:
   - Users can input grades between 0 and 100 for multiple subjects or assignments.
   - Grades are stored dynamically using an `ArrayList`.

3. Average Grade Calculation:
   - Computes the average of all entered grades and handles empty lists gracefully by returning 0.

4. Grade Performance Metrics:
   - Converts the average grade into a corresponding **letter grade** (`A`, `B`, `C`, `D`, or `F`).
   - Calculates the **GPA** on a 4.0 scale based on the average grade.

5. User-Friendly Error Handling:
   - Ensures only valid grades (0–100) are accepted.
   - Provides informative feedback when no grades are available.

6. Exit Option:
- Allows users to safely exit the program.

  
 Program Flow:
1. Welcome Message:
   - The user is greeted with a welcome message and menu options.

2. Adding Grades:
   - Users choose option `1` to input grades.
   - Validation ensures grades fall within the acceptable range (0–100).

3. Calculating the Average:
   - Users select option `2` to view the average of all entered grades.

4. Displaying Grade Information:
   - Option `3` displays:
     - Average grade.
     - Corresponding letter grade.
     - GPA on a 4.0 scale.

5. Exiting the Program:
   - Selecting option `4` terminates the program with a farewell message.

Code Highlights:

Dynamic Grade Storage:Uses `ArrayList<Double>` to allow flexible storage and management of grades.
Reusability:Functions like `calculateAverage`, `getLetterGrade`, and `calculateGPA` modularize the code for better maintainability and reusability.
Validation:Ensures robust input validation for grades and menu choices.


Technologies Used:
- Language:Java
- Tools:Java Development Kit (JDK), Console for user interaction

Potential Enhancements:
1. Persistent Storage:
   - Add file handling to save and retrieve grades across sessions.
2. Graphical Interface:
   - Integrate with a GUI framework like JavaFX or Swing for enhanced user experience.
3. Subject-specific Grades:
   - Allow users to input and manage grades per subject.
4. Reports:
   - Generate detailed reports, including grade trends and summaries.

This program is a foundational tool for managing student performance and can be expanded for more sophisticated use cases. Let me know if you'd like to implement any enhancements or need further clarification!
