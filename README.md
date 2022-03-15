# CP363 Database Project

## Project Description
Student Record Database Management System. The database  would  contain  general  student  information  (such  as  name,  address, contact information, admission year, courses, major(s) etc.), attendance information, grade information, scholarship information, etc. The above information is just examples. It is your responsibility to design the database. However, it will be better that the database you design has information for students who are taking both major and minor degrees. It will be better that the database you design has the information of domestic and international students. 

## Technologies
* MySQL
* DOM Compand Prompt 
* Lucidchart (diagram design)
* Notepad++

## Entity-Relationship Diagram
![image](https://user-images.githubusercontent.com/61894684/158472874-5e1d8829-fa05-4578-9ce0-5a12f36960bc.png)

## Conceptual Design Diagram
![image](https://user-images.githubusercontent.com/61894684/158473031-41f9e904-a4bd-49fb-8a01-847d088b7ed1.png)

## Test Cases:
Problem: Find student names who enrolled in Database's course in September 2021

> Solution 1:
> Uses the WHERE clause where we select first & last name from student, course name & starting date. We then move to WHERE, which has conditions. These conditions are to determine if the student's primary key matches the foreign student id key from current course and see if the current course date is in September, we can see this from the image below:
![image](https://user-images.githubusercontent.com/61894684/158473311-21c4d863-02a6-4fc2-a621-782d06c1b1f1.png)

> Solution 2:
> Uses the explicit JOIN technique where we combine rows from two or more tables, based on related attributes between them. In our case, we join the Student and CurrentCourse table together and use the WHERE condition to see if the start date for the database class is in September, we can see this in the image below:
![image](https://user-images.githubusercontent.com/61894684/158473469-00de6068-b526-4ad7-ae8f-64c0f67847d8.png)




## Contributors 
* Christopher Rossi
* Paige Broussard
* Jonathan Pilarski
* Karan Singh
