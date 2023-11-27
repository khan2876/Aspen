# Overview  
The goal is to read in a data file with information about teachers and students in a fictional school.  Later, we will add more functionality to this school (classes, grades, etc.)

# Create classes  
Create three classes, one for a School, one for a Teacher and another for a Student.  

## Teacher class (2 pts)  
A Teacher has a last name, first name, room number, and a hire year.
* getFirstName()
* getLastName()
* getRoomNumber()
* numYearsEmployed() : 2023 - hire_year  

## Student class (2 pts)  
A Student has a last name, first name, LASID, and a year of graduation.
* getFirstName()
* getLastName()
* getLASID()
* numYOG()  

## School class (3 pts)  
A School contains an array of Teacher objects and an array of Student objects.
* Constructor that takes a filename with the data about people in the school and creates the Teacher and Student objects
* numStudents() - gives the number of students in the school
* numTeachers() - gives the number of teachers in the school

# Data file  
The first line of the file tells how many students and teachers are in the school.  The first number is the number of students and the second is the number of teachers.  
Each of the following lines in the file has data for either a Teacher or a Student.  

# Commit Regularly (3 pts)  
Make at least 4 commits in a class period.  There's some leeway about when you should do this.  You can do this every 15 minutes, or as you complete different parts of the assignment.  
Please don't copy/paste code from other assignments.  You're welcome to refer to previous assignments, but you will remember more if you retype rather than copy blindly.  

