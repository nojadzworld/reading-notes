# Room

What database engine is Room wrapped around? Do you think this is a good choice? Why or why not?

Built around SQLite and it is a good choice based on its efficiency, stability, and compatibility with various platforms, including Android. 

Do Rooms have any similarities to JPA?

Annotation-based mapping: Both Room and JPA use annotations to map Java objects to database tables.

Querying capabilities: Room and JPA provide ways to execute database queries using either SQL-like query languages or method-based query creation. 

Entity relationships: Both Room and JPA support defining relationships between entities, such as one-to-one, one-to-many, and many-to-many relationships. 

Caching and performance optimizations: Room, similar to JPA implementations, offers caching mechanisms to improve performance. 

Describe a DAO in your own words

. It is a design pattern that separates the persistence logic from the business logic in an application