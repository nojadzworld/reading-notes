# API's

## API Design Best Practices

What does REST stand for?
 **Representational State Transfer**
REST APIs are designed around a ____.
**around resources, which are any kind of object, data, or service that can be accessed by the client.**
What is an identifier of a resource? Give an example.
**URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: https://adventure-works.com/orders/1**
What are the most common HTTP verbs?
**GET, POST, PUT, PATCH, and DELETE.**
What should the URIs be based on?
**on parameterized URI paths**
Give an example of a good URI.
**https://adventure-works.com/orders**
What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
**The more requests, the bigger the load. Retrieving large objects can increase the latency of a request and incur additional bandwidth costs**
What status code does a successful GET request return?
**HTTP status code 200 (OK)**
What status code does an unsuccessful GET request return?
**the method should return 404 (Not Found).**
What status code does a successful POST request return?
**it returns HTTP status code 201 (Created).**
What status code does a successful DELETE request return?
*server should respond with HTTP status code 204 (No Content***

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)