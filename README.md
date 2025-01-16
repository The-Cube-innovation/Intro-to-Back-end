# Intro-to-Back-end

PART 1
Definition Questions

What is backend development, and how does it differ from frontend development?
Define the term API and explain its role in web development.
What is a database, and why is it essential in backend systems?
Explanation and Functionality Questions
What is the role of a server in a backend system?
Explain the difference between authentication and authorization in web applications.
What is REST, and why is it widely used in backend development?
How do backend frameworks simplify the development process? Provide an example.

Practical/Scenario-Based Questions

If a website requires user login, which backend concepts would be involved in implementing it?
Imagine you are building an e-commerce site. What backend components would you use to handle orders and inventory?
How would you ensure the scalability of a web application as the number of users increases?
Comparative Questions
Compare relational and non-relational databases with examples of each.
What are the advantages of using Node.js for backend development compared to other languages like PHP?
Critical Thinking Questions
Why is security a critical concern in backend development? Provide examples of potential threats.
How can middleware improve the functionality and maintainability of backend systems?
What factors should be considered when choosing a backend framework or language for a project?

PART 2

Introduction & Foundational Skills (Focus on Project Relevance)
Welcome to Week 1! This week, we’ll be diving into the exciting world of SQL and databases! We’ll explore what SQL is used for, how it benefits web applications, and the building blocks of databases: tables, columns, and data types. But most importantly, we’ll get hands-on experience by creating a basic database structure for our upcoming project!


Learning Objectives:
Understand the purpose and applications of SQL, particularly for web applications.
Identify the fundamental components of a database: tables, columns, and data types.
Design a basic database schema for our project.

Instructions
This assignment is designed to be completed in approximately 2 hours.

What you’ll need:
Access to a computer with internet access
A code editor (e.g., Visual Studio Code)
Drawing software (e.g., Draw.io, Visual Paradigm) for the bonus question.

Submission
Clone the project on your local computer
Create a file named answers.sql
Run the queries on MySQL workbench and once they are successfull copy and paste on the answers.sql file on VS code
Make sure you clearly comment your answers. Example:
-- question 1.1
CREATE TABLE table_0 (
    column1 datatype,
    column2 datatype
);

-- question 1.2
CREATE TABLE table_1 (
    column1 datatype,
    column2 datatype
);
Once you finish the assignment, push the code to github

Part 3: Database Modelling
Using a software of choice eg. draw.io, lucid chart etc, draw a well defined Entity Relationship Diagram (ERD) model a database of your choice an exampleof tables patient and providers is given. Once you are done export or download the diagram in pdf format and upload it on the repository or you can copy and paste it to the cloned repository before you push the changes

Example:

Table Name: patients

FIELD	DATA TYPE	CONSTRAINTS
patient_id	INT	PRIMARY KEY, AUTO_INCREMENT
first_name	VARCHAR	NOT NULL
last_name	VARCHAR	NOT NULL
date_of_birth	DATE	NOT NULL
gender	VARCHAR	NOT NULL
language	VARCHAR	NOT NULL


Table Name: providers

FIELD	DATA TYPE	CONSTRAINTS
provider_id	INT	PRIMARY KEY AUTO_INCREMENT
first_name	VARCHAR	NOT NULL
last_name	VARCHAR	NOT NULL
provider_speciality	VARCHAR	NOT NULL
email_address	VARCHAR	
phone_number	VARCHAR	
date_joined	DATE	NOT NULL





Part 4: Creating a database
Now that you have already created a model of your database, it is time to bring it start building on it. Create database named hospital_db.




Part 5: Creating Tables
After creating your your database the next step is creating your tables, but before we start making any changes to the database, we need to make sure it is selected. Select the database using the USE keyword.
After selecting the databse proceed to create the tables using the information provided in the tables above. For Example

CREATE TABLE patients(
    patient_id INT PRIMARY KEY AUTO_INCREMENT,
    first_name VARCHAR(50) NOT NULL,
    last_name VARCHAR(50) NOT NULL,
    date_of_birth DATE NOT NULL,
    gender VARCHAR(10),
    language VARCHAR(20) NOT NULL
);
