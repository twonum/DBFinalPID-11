
## Student Academic Performance Analysis System

### Description

The Student Academic Performance Analysis System is a comprehensive database project developed using C# WinForms with SQL Server integration for data storage and Power BI for data analytics. It aims to design and implement a robust database schema to manage student enrollment, academic records, assessments, and related activities within an educational institution. This project provides detailed insights into database design, normalization, entity-relationship modeling, and optimization strategies employed.

### Project Overview

The "Student Academic Performance" project is designed to efficiently manage and track academic performance data for students within an educational institution. It encompasses a relational database schema that organizes data related to students, courses, assessments, feedback, and academic records.

### Project Objectives

- Efficiently manage student information including enrollment details, academic records, and performance assessments.
- Facilitate communication and interaction between students, instructors, and advisors through appointment scheduling and feedback mechanisms.
- Provide a comprehensive framework for tracking course offerings, learning outcomes, and program assessments.

### Database Entities

1. **SystemUser**: Represents system users such as students, advisors, and instructors with associated login credentials and roles.
2. **Student**: Tracks student-specific details including registration information, personal data, and academic records.
3. **Advisor**: Manages advisors responsible for mentoring and guiding students, facilitating appointments, and feedback.
4. **Instructor**: Represents instructors responsible for teaching courses, defining learning outcomes, and receiving feedback.
5. **Courses**: Defines academic courses with associated instructors and enrollment details.
6. **Course Learning Outcome**: Describes specific learning outcomes associated with each course.
7. **CLO Assessment**: Tracks assessments related to course learning outcomes.
8. **Student CLOAssessmentOutcome**: Records individual student outcomes for course assessments.
9. **Programs**: Represents academic programs offered by the institution.
10. **Program Learning Outcome**: Defines overarching learning outcomes associated with academic programs.
11. **Student PLOAssessmentOutcome**: Tracks student performance against program learning outcomes.
12. **Enrollments**: Manages student enrollments in courses with associated grades and semester details.
13. **Semester**: Represents academic terms or semesters during which courses are offered.
14. **Grade Scale**: Defines a grading scale used for assessing student performance.
15. **PLO Assessment**: Tracks assessments related to program learning outcomes.
16. **Student Semester Record**: Records student academic performance and GPA for each semester.
17. **Appointment**: Facilitates scheduling of appointments between students and advisors.
18. **Course Offering**: Manages course offerings within specific semesters.
19. **Attendance**: Tracks student attendance in courses.
20. **Feedback**: Allows students to provide feedback on advisors and instructors.
21. **Department**: Represents academic departments offering programs and courses.

### Project Scope

The project involves the design and implementation of a relational database schema conforming to normalization principles. It includes the development of data models, entity-relationship diagrams, and database tables to capture and manage student academic data effectively. Considerations for user roles, authentication, and authorization are also included to ensure secure access to the database system.

### Project Deliverables

- Creation of a robust database schema comprising tables, relationships, and attributes for storing academic performance data.
- Documentation including entity definitions, attribute specifications, and relationship mappings.
- Implementation of CRUD (Create, Read, Update, Delete) operations to interact with the database via a user interface or application programming interface (API).
- Testing and validation of the database system to ensure data integrity, performance, and usability.

### License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

### Author

- twonum(https://github.com/twonum)
