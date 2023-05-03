# Related data in Spring

Name a few real life examples of “One To Many” relatioships.

- A person can have many credit cards, but each credit card is associated with only one person.
- A company can have many employees, but each employee works for only one company.

Given two entities, one named Player and one named Team, if you wanted to create a one to many relationship with those entities which would be the one and which would be the many?

- The one would be Team and the player would be many

Explain one to many relationships to a non-technical friend.

- A library has many books and each book belongs to a speficic author. The one side is the author and books is the many.

## Baeldung: Spring Integration Testing

Describe the difference between a unit test and an integration test.

- A unit test is a type of test that focuses on testing individual components or units of code in isolation from the rest of the system.

-  An integration test is a type of test that focuses on testing how different components of a system work together.

What is the object that provides support for Sprin MVC Testing?

- MockMvc. It's a part of the Spring Test framework and is used to test Spring MVC controllers by simulating HTTP requests and responses. The MockMvc object allows developers to write tests that mimic a user's interaction with a web application, without actually having to deploy the application to a server.

What does the “perform()” method do in a Spring integration test?

-  used to perform a mock HTTP request to a Spring MVC controller. It allows developers to test the controller's response to different HTTP methods (e.g. GET, POST, PUT, DELETE) and different request parameters. The "perform()" method returns a "ResultActions" object, which can be used to verify the response from the controller and to perform additional assertions on the result.