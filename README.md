Download Link: https://assignmentchef.com/product/solved-dbs211-lab8-sql-erd
<br>
<h1>Objectives:</h1>

The purpose of this lab is to introduce the students to the formal UML Entity Relationship Diagram.  This diagram is a Database Design diagram and show the entities, relationships, and cardinalities for the proposed database.  By the end of this lab, the student will be able to:

<ul>

 <li>work with a simple scenario to find the entities and the relationship between entities.</li>

 <li>define the relationship cardinality and optionality.</li>

 <li>design a simple database using an ERD model.</li>

 <li>simulate many-to-many relationships with in an ERD.</li>

</ul>

<strong>Tasks:</strong>

Draw the corresponding crow’s foot ERD for the following scenario. Many-to-Many relationships should be broken into two 1-to-Many relationships using a bridge or junction entity. Label PK attributes and FK when applicable, use bold to indicate required fields.

<strong>Bridge/Junction Entity:</strong> The <strong>bridge/junction</strong> entity is used to eliminate the many-to-many relationships. This <strong>entity</strong> sits between the two <strong>entities</strong> with the many-to-many relationship and this composite <strong>entity</strong> shares the primary keys from both tables.

<strong>Show all PK’s and FK’s with your solution.</strong>

First you need to find all entities. Next, list the attributes for each entity. Next, you need to find the relationship between each two entities if there is any relationship. Fix all <em>many-to-many</em> relationships. Finally, make sure all PKs and FKs are properly defined.

<em>For all entities</em>, list their attributes. For example, for the students, we need to store student ID, student name and last name, email address, address, and phone number. You do not need to define all possible attributes. Just determine some important attributes.

<em>For each entity</em>, you need to define a primary key. If there is a relationship between two entities make sure you define the corresponding foreign key in the child table.

<ul>

 <li><strong><em>Seneca College</em></strong> contains many departments.</li>

 <li>Each department has many programs, but every program belongs to only one department.</li>

 <li>Every department has many professors.</li>

 <li>A professor can work for only one department.</li>

 <li>A program has many courses.</li>

 <li>A course can be a requirement of many programs.</li>

 <li>A professor can teach many courses. A course can also be taught with many professors, via sections.</li>

 <li>Each section is only taught by one professor (ignore the summer term)</li>

 <li>A program has many students studying in that program.</li>

 <li>A student can study multiple programs. However, a student must register in at least in one program.</li>

 <li>A student may take many courses.</li>

 <li>A student, however, can be off from school and do not take any courses.</li>

 <li>A course can be taken by many students.</li>

 <li>A new course may not be available yet so the course may not be taken by any student.</li>

 <li>A student may have a program advisor. Having an advisor is optional for students so some students may not have any advisor.</li>

 <li>An advisor can have one or more students assigned to them.</li>

</ul>








