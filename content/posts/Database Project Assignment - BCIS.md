+++
title = "Database Project Assignment - BCIS"
tags = ["SQL", "Information Systems", "Database", "ERD", "Projects", "COMP508"]
date = "2024-03-11"
+++


### COMP508: Database System Design - Database Project Assignment - A+ level (100%)

Below is the Database Project Assignment for the COMP508 paper. If the preview does not work, click the link [here](https://drive.google.com/file/d/1Fd2PsxkyvDJ6JwFDemk_Vgfrp7AHqJ9q/view).
{{< shortcodesnippet >}}

    <iframe src="https://drive.google.com/file/d/1Fd2PsxkyvDJ6JwFDemk_Vgfrp7AHqJ9q/preview" width="640" height="480" allow="autoplay"></iframe>

{{< /shortcodesnippet >}}

#### Summary

This project involved

1. Analysing a case study to develop the business rules
2. Designing a logical Entity Relationship Diagram
3. Creating tables in Oracle SQL 
4. Populating the tables with data
5. Constructing SQL queries, working with the populated data

{{< details "Case Study for Database Project Assignment" >}}

"A major faculty consisting of many Departments in the Whangarei University of Technology
(WUT) has approached you for the design and implementation of a relational database
system. The requirement collection and analysis phase of the database design process
provided the following data requirements for the faculty’s proposed database system.

WUT offers many programmes (e.g., Bachelor of Science, Bachelor of Information
Technology, Bachelor of Software Engineering, Bachelor of Computer and Information
Sciences). The information to be stored for a programme is: programme code, level, points,
duration (in years), campus, and semester.

Each department runs several programmes. Each programme uses several courses (e.g.,
Programming I, Database System Design), but not every course is offered every
semester/year to students. A course can be offered in more than one programme, and a
programme may offer many courses. The information to be stored about a course is: course
code, course name, and course credits.

Each programme is managed (e.g., a Programme Director) by a member of the academic staff,
and each course is coordinated by a member of the academic staff also.

A student can enrol in one programme only at a time. Once enrolled a student is assigned a
unique student identification number. To complete a programme, each student must
undertake and pass all the required courses in the programme. This requires that the
database store the performance (pass or fail) of each student in every programme.

Additional data stored on each student includes student name (first and last), address (town,
street, and postcode), date of birth, gender, and student financial loan (Yes or No). For
emergency purposes, the database stores the last name, first name, address, phone, and
relationship of each student’s next-of-kin. Assume that every next-of-kin is a next-of-kin of
one student only.

Each department is led by an academic staff member (e.g., the Head of the Department). The
database should record the date the staff member started the role as Head of the department.
Each department has a name, code, phone number, and location (e.g., Z Building). Each
department employs many members of academic staff. An academic staff member works for
one department only.

An academic staff member can be the director of at most one programme but can be the
coordinator of more than one course. An academic staff member may not be assigned any of
the above mentioned roles (such as Course Coordinator, Programme Director, Head of the
Department). All members of the academic staff teach courses. Every member of the
academic staff may teach zero, one or more courses, and a course may be taught by more
than one academic staff member. The database should record the number of hours an
academic staff member spends teaching each course per week. The information to be stored
for an academic staff member is: staff number, name (first and last), employment start date,
phone extension number, office number, gender, salary, position (e.g. Lecturer, Senior
Lecturer, Professor), and highest qualification."

{{< / details >}}