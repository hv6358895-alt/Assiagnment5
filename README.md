
# University Course Registration System Using Neo4j

## Project Description
This project implements a University Course Registration System using Neo4j graph database and Cypher query language.

It represents students, faculty members, courses, and departments as nodes and connects them using graph relationships.

## Technologies Used
- Neo4j AuraDB
- Cypher Query Language
- GitHub

## Node Labels
- Student
- Faculty
- Course
- Department

## Relationships
- ENROLLED_IN: Student -> Course
- TEACHES: Faculty -> Course
- BELONGS_TO: Student -> Department
- OFFERS: Department -> Course

## Features
- Create students, faculty, courses, and departments.
- Establish relationships between nodes.
- Store enrolment grades and semesters.
- Store faculty academic years.
- Retrieve students and courses using filtering queries.
- Calculate faculty teaching loads.
- Count student enrolments per course.
- Verify graph nodes and relationships.

## How to Run
1. Create a Neo4j AuraDB instance.
2. Open Neo4j Browser and connect to the database.
3. Open `course_registration.cypher`.
4. Copy and execute the setup queries first.
5. Execute the verification and retrieval queries individually.

## Expected Results
- 5 Student nodes
- 2 Faculty nodes
- 5 Course nodes
- 2 Department nodes
- 26 Relationships

## Conclusion
The system demonstrates how graph databases represent university entities and their relationships. Cypher queries provide efficient retrieval and analysis of course registration data.
