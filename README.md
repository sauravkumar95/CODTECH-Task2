## PERSONAL DETAILS :
  #### Name : SAURAV KUMAR
  #### Company : CODTECH IT SOLUTIONS
  #### ID : CT04PP2323
  #### Domain : PYTHON PROGRAMMING
  #### Duration : 15th June 2024 to 15th July 2024
  #### Mentor : SRAVANI GOUNI

## OVERVIEW OF THE PROJECT

  ### PROJECT : Student Grade Tracker
  ### OBJECTIVE :
  The objective of the project is to create a Develop a Python program to track and manage student grades.
  The program should allow the user to input grades for different subjects or assignments, calculate the
  average grade, and display the overall grade along with any additional information (such as letter grade or GPA).
 
  

## EXPLANATION OF CODE :
  ### Functions :
    1. calculate_average(grades):
      . This function takes a list of grades as input.
      . It calculates the total sum of all grades using sum(grades).
      . It returns the average by dividing the total by the number of grades using len(grades).
      
    2. get_letter_grade(average):    
      . This function takes the average grade as input.
      . It checks the average against a series of conditions to determine the corresponding letter grade:
        . If the average is greater than or equal to 90, it returns 'A'.
        . If the average is greater than or equal to 80, it returns 'B'.
        . If the average is greater than or equal to 70, it returns 'C'.
        . If the average is greater than or equal to 60, it returns 'D'.
        . If the average is below 60, it returns 'F'.

  ### Main Function :
    The main() function is the entry point of the program and contains the following steps:
      1. It prints a welcome message to the user.
      2. It prompts the user to enter the student's name using input().
      3. It prompts the user to enter the number of subjects using input() and converts it to an integer using int().
      4. It creates an empty list called grades to store the grades for each subject.
      5. It uses a for loop to iterate num_subjects times:
          . In each iteration, it prompts the user to enter a grade for the current subject using input().
          . It converts the input to a float using float() and appends it to the grades list.
      6. It calls the calculate_average(grades) function to calculate the student's average grade and stores the result in the average variable.
      7. It calls the get_letter_grade(average) function to determine the student's letter grade based on the average and stores the result in the letter_grade variable.
      8. It prints the student's name, average grade (formatted to 2 decimal places), and letter grade.
      9. It determines the student's GPA based on the letter grade:
          . If the letter grade is 'A', the GPA is set to 4.0.
          . If the letter grade is 'B', the GPA is set to 3.0.
          . If the letter grade is 'C', the GPA is set to 2.0.
          . If the letter grade is 'D', the GPA is set to 1.0.
          . If the letter grade is 'F', the GPA is set to 0.0.
      10. It prints the student's GPA (formatted to 2 decimal places).

Finally, the if _name_ == "_main_": block ensures that the main() function is only executed when the script is run directly (not imported as a module).
  This program demonstrates the use of functions, user input, calculations, and conditional statements in Python to create a simple student grade tracking system.

## RUN THE CODE :
  For writing and running the code,I used an IDE(vs code),a text editor with Python support 

![Screenshot 102](https://github.com/sauravkumar95/CODTECH-Task2/assets/175045159/e8411d5d-c46d-4b38-abce-bc3a709dbdc8)
