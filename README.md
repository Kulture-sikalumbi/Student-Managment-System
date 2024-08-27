# Student-Managment-System
The code in this repository is for a simple student managment system that allows the user to add new student,update student details, delete student , view all students in the system.
# How to run the System(Code)
firstly please make sure Git is installed on your machine before trying to clone this repository!

-step1: clone the repository by copying the repository  link and then paste and run it in your terminal. 

-step2: Navigate to the files directory by pasting and runing this command:

cd Student-Managment-System 

-step3: Finaly execute the following command in your terminal:

python Studentmanagmentsystem.py

ALL set the  Student managment Sytem is now running!
# all commands
1: git clone https://github.com/Kulture-sikalumbi/Student-Managment-System.git

2: cd Student-Managment-System 

3: python Studentmanagmentsystem.py

  Altenatively you can just navigate to the code's file , copy and  paste the code  in your IDE and run it on your machine !
  # All changes that were made to code
  1.The students class had too many responsibilities therefore all the methods in the students  class were separated to into different classes based on their functionality, made  separate classes for updating ,adding and displaying student details.This was done to adhere to the single responsibility principle.
  
  2. created a separate utility function, update_student_attributes, which encapsulates the logic for updating student attributes (name, age, and major).Both the StudentUpdater class and the StudentManagementSystem class use this function without duplicating the same checks.This was done to make the code adhere to the Don't repeat youself principle.
     
  4. Added an IStudentRepository interface class for all student operations. The IStudentRepository  works as an Abstraction layer between the student managment system class and the student database class . This was done to remove the direct  dependancy that student managents system class had on the student database class ,and therfore adhered to the dependancy inversion principle.
     
  5. Finally a menue was added to the systems code to improve user interaction, the menue has options for:
     
  - adding a new student to the system
   
  - updating students details
    
  - dispalying all students
    
  -viewing a students details

  - deleting student from the system

  - exiting the system



