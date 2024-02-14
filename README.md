The ER diagram shows the following entities: Employee (Ssn primary Key), Department(Dnum primary Key), Project(Pnum primary Key) and Role(Rname primary Key). The first three are strong entities and Role is a weak entity.
Employee has a 'Works for' relationship with Department, 'Manages' realtionship with Department.
Department has 'Controls' relationship with Project.
Employee and Project have a 'Works On' relationship.
Role being a weak entity is dependent on Employee with a 'Has' relationship.
After using the rules of mapping six tables are obtained:
1.EMPLOYEE  2.PROJECT  3.DEPARTMENT  4.ROLE  5.WORKS_ON  6.HAS

Create directory shows the creation of all the tables and addition of data (1000 rows) in Postgresql.
Delete shows deleting one row in each of the tables.
Insertion shows adding a data to the existing tables
Select directory select rows with and without condition
Update directory shows changing an exising row.
