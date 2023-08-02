*Assignment :*

- To complete the project successfully, you must demonstrate that you have the skills to design a database from a new set of data, including creating an ERD to identify entities, attributes, and relationships. You will normalize tables, create your database, and load some data. You will also demonstrate some database management tasks by working with views
**Learning Objectives :**
- Explain the importance of a good database design.
- Create an ERD of a database.
- Generate and execute an SQL script from an ERD to create a schema.
- Load a database schema with data.
- Identify entities and attributes.
- Normalize tables.
- Define keys and relationships.
- Build database objects by generating and running an SQL script the pgAdmin ERD Tool.
- Create a view and a materialized view and export from each data.
- Import data into a Db2 database and a MySQL database.
- Evaluate the completeness and technical correctness of the database design and implementation performed by your peers using the provided rubric and grading scheme.

**There are three key steps in the database design process:**
- Requirements analysis – where you analyse the data you are working with and the requirements for the use of that data,
- Logical design – where you plan how to organise your data,
- Physical design – where you plan how to implement your logical design in the database management system you will be using.

-  Most OLTP systems are normalized to the third normal form for optimal transactional performance. Whereas OLAP systems are generally denormalized to enhance read performance.

## **Hands-on Lab: Database Design using ERDs**
- This Lab will demonstrate how to design a database generating Entity Relationship Diagram (ERD) with PostgreSQL.
- To complete this lab you will utilize PostgreSQL relational database service available as part of IBM SN Labs Cloud IDE. IBM Skills Network Labs (SN Labs) is a virtual lab environment used in this course.
- In this lab, you will learn how to design a database by creating an entity relationship diagram (ERD) in the PostgreSQL database service using the pgAdmin graphical user interface (GUI) tool.
- create an ERD of a database. generate and execute an SQL script to create the database schema from its ERD. load the created database schema with data.

[Hands-on Lab : Database Design using ERDs](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0110EN-SkillsNetwork/labs/Lab%20-%20Database%20Design%20using%20ERDs%20/instructional-labs.md.html)


## **Final Graded Project:**
- Scenario :
In this scenario, you have recently been hired as a Data Engineer by a New York based coffee shop chain that is looking to expand nationally by opening a number of franchise locations. As part of their expansion process, they want to streamline operations and revamp their data infrastructure.

Your job is to design their relational database systems for improved operational efficiencies and to make it easier for their executives to make data driven decisions.

Currently their data resides in several different systems: accounting software, suppliers’ databases, point of sales (POS) systems, and even spreadsheets. You will review the data in all of these systems and design a central database to house all of the data. you will then create the database objects and load them with source data. Finally, you will create subsets of data that your business partners require, export them, and then load them into staging databases that use different RDBMS.














