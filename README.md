# Overview  
The goal is to read in a data file with information about teachers and students in a fictional school.  Later, we will add more functionality to this school (classes, grades, etc.)

# Create classes  
Create three classes, one for a School, one for a Teacher and another for a Student.  

## Teacher class (2 pts)  
A Teacher has a last name, first name, room number, and a hire year.
* String getFirstName()
* String getLastName()
* int getRoomNumber()
* int numYearsEmployed() : 2023 - hire_year  

## Student class (2 pts)  
A Student has a last name, first name, LASID, and a year of graduation.
* String getFirstName()
* String getLastName()
* int getLASID()
* int numYOG()  

## School class (4 pts)  
A School contains an array of Teacher objects and an array of Student objects.
* Constructor that takes a filename with the data about people in the school and creates the Teacher and Student objects
* int numStudents() - gives the number of students in the school
* int numTeachers() - gives the number of teachers in the school
* void listStudents(String school) - prints a list of students in a particular school

# Data file  
The first line of the file tells how many students and teachers are in the school.  The first number is the number of students and the second is the number of teachers.  
Each of the following lines in the file has data for either a Teacher or a Student.  

# Commit Regularly (3 pts)  
Make at least 4 commits in a class period.  There's some leeway about when you should do this.  You can do this every 15 minutes, or as you complete different parts of the assignment.  
Please don't copy/paste code from other assignments.  You're welcome to refer to previous assignments, but you will remember more if you retype rather than copy blindly.  

# Testing (1 pt)
Create JUnit tests to verify that numStudents() and numTeachers() work properly.  
For the other methods, you can create a separate class with a main method that allows you to see if each method is returning/printing properly.  This is not required, but it's probably a good idea.  

# Submit
3 classes (Student, Teacher, School) and one testing file  

