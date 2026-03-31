
Table of Contents

About the Project

Setup Guide

 Highlights

 Concepts in Action

 Author

Credits




About the Project

The Campus Course & Records Manager (CCRM) is a command-line based system created to simplify academic management tasks.

It allows users to efficiently handle student data, course listings, enrollments, and grading, all through a streamlined CLI interface. The goal of this project is not just to build a working system, but to demonstrate how core Java concepts and modern APIs can be applied to solve real-world problems.

From structured object-oriented design to efficient file handling and data processing, CCRM reflects practical Java development in action.




Setup Guide

 Requirements

Java Development Kit (JDK) version 21 or above


 Steps to Run

1. Clone the repository

git clone https://github.com/SAMQ-debug/Vityarthi-Programming-in-Java/edit/main/README.md

2. Import into Eclipse

Navigate to File > Import > General > Existing Projects into Workspace

Select the project folder you just cloned


3. Compile the source code

javac -d bin src/edu/ccrm/cli/Main.java

4. Run the application

java -ea -cp bin edu.ccrm.cli.Main

 Tip: You can use the sample CSV files in the test-data folder to quickly test features.



Highlights

Manage Students & Courses
Create, modify, and delete records with ease.

Enrollment Handling
Enroll students into courses while automatically checking constraints like maximum credit limits.

Grade Management System
Assign and update grades for enrolled students.

Data Import & Export
Work with CSV files and maintain backups effortlessly.

Additional Functionalities

Fast data filtering using Streams

Clean and interactive CLI design

Directory size calculation utility



Concepts in Action

This project acts as a hands-on implementation of important Java and software engineering concepts.



Java Platform Overview

Platform	Description	Typical Usage	Role in CCRM

Java ME	Lightweight Java version	Embedded systems, IoT	Not used
Java SE	Standard Java platform	Desktop & CLI applications	Core platform used
Java EE	Enterprise-level extensions	Web apps and services	Not required



 Understanding JDK, JRE, JVM

JDK → Complete development package including compiler and tools

JRE → Environment required to execute Java programs

JVM → Executes bytecode and ensures platform independence


These components together make Java portable across different systems.



 Concept Mapping in Code

Concept	Implementation Area

Encapsulation	Person class (private members)
Inheritance	Student class extending Person
Abstraction	Abstract base class Person
Polymorphism	TranscriptService
Streams API	CourseService
NIO.2 File Handling	ImportExportService
Design Pattern	AppConfig (Singleton pattern)
Exception Handling	EnrollmentService


 Author

Samaira Quadry

GitHub: @SAMQ-debug


 Credits

Java SE Documentation

Eclipse IDE

GitHub

 Developed as part of the Vityarthi Programming in Java course, combining learning with practical implementation.
