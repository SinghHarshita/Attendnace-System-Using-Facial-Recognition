# Attendance System Using Facial Recongnition
Facial recognition based attendance system which was developed as a part of Python lab curriculum. This system detects and recognises the faces of students and marks their attendance. A very efficient system that seeks to simplify the jobs of teachers.

This project uses tkinter module of python to provide the interface.

## Dependencies
1. Python : tkinter module, mysql-connector, matplotlib
2. Mysql database

## Database
1. views.py is the file with all database connectivity
2. Make changes in this file to connect to your database

`Note : The project will only run efficiently when it is connected to the database`

## Starting the project
Run the following command in the command prompt :

`python MainPage.py`

This will open the tkinter window and the project will be up and running.

## Adding a new student 
### CLI
To add a new student and train the model for that student, execute

`python new_user.py`

This is the cli way to add new users.

### GUI
The class teacher of the student can add the student. The project when in execution, has the interface to add new students.
