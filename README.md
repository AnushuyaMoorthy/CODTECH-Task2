Name: Anushuya M
Company: CODTECH IT SOLUTIONS
ID:CT08PP467 Domain:Python programming
Duration: May-June 2024
Mentor: Sravani Gouni


Overview for the project Student Grade Tracker

This Python program is designed to track and manage student grades. It allows users to input grades for different subjects or assignments, calculates the average grade, and displays the overall grade along with additional information such as the letter grade and GPA. The program operates via a simple command-line interface (CLI) and includes the following main components:

Function to Calculate Average Grade:

The calculate_average(grades) function takes a list of grades and returns their average. If the list is empty, it returns 0.
Function to Determine Letter Grade:

The determine_letter_grade(average) function converts an average grade into a letter grade based on predefined thresholds (A, B, C, D, F).
Function to Convert Letter Grade to GPA:

The letter_to_gpa(letter_grade) function maps each letter grade to its corresponding GPA value using a predefined dictionary.
Main Program:

The main() function facilitates user interaction. It prompts the user to input subject names and grades until the user types 'done'. It then validates the input, calculates the average grade, determines the corresponding letter grade, converts it to GPA, and displays the results.
Conclusion
This Python program provides a straightforward solution for managing student grades. By leveraging simple functions and a command-line interface, it effectively tracks grades, calculates averages, and provides additional academic performance indicators such as letter grades and GPA.

Here is a quick summary of the program's key features and benefits:

User-Friendly Input: The program prompts users to input subject names and grades interactively.
Validation: Ensures grades entered are numeric and within a valid range (0 to 100).
Comprehensive Feedback: Calculates and displays the average grade, letter grade, and GPA.
Modular Design: Functions are clearly separated, making the code easy to understand and maintain.
The program can be further extended to include more features, such as saving the grades to a file or database, handling multiple students, or providing a graphical user interface (GUI) for better user experience.
