# Accessing Data with JPA

How are query methods defined when using Spring Data JPA?

- by declaring their method signature.

Which dependencies will you need in order to complete the Spring guide?

- Spring Data JPA & H2 Database

What annotations are used to specify an auto generated identification number for an Entity?

- @GeneratedValue and id

## Baeldung: Comparing repositories 

Which of the Spring Data Repositories covered in the readings has the most methods available to it?

- CRUD and JPA

Name a downstide of a Spring Data Repository.

- we couple our code to the library and to its specific abstractions, such as `Page` or `Pageable`; that's of course not unique to this library – but we do have to be careful not to expose these internal implementation details

How would you define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository?

- findAll(...)

****

CRUD - Create, Read, Update and Delete

Postgres -> SQL -> Structured Query Language

- psql in terminal
- PgAdmin

JPA (Java Persistence API) + Hibernate 

application.properties

- defining DataSource

PgAdmin

- Open database go to schema and then tables
- Click on view data button