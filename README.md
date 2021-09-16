COURSE REGISTRATION FORM USING PYTHON GUI AND MYSQL

This is a GUI project created by using Python GUI Tkinter and MySQL database. 

Requirements

For successful functioning of the application please complete the following requirements:

i.	Install the following libraries: tkinter, mysql.connector, time, functools.

ii.	After installing the required libraries, you need to create a database and connect it to the code. To create the required database, follow the steps mentioned below:

a.	Create a new database with the name “Course”.

b.	Use this code to create table under this database:
     create database Course;
     use Course;
     create table if not exists Course.login(username_info  varchar(50),password_info varchar(50),course_name varchar(50),course_type varchar(50),course_duration varchar(50));

