# CRUD

## Status Codes Based On REST Methods 

In your own words, describe what each group of status code represents:

100’s = info status code basically saying that the request was received and the server will try to provide an answer back

200’s = success code letting the client know that the request was accepeted

300’s = redirection codes. client needs to issue request to the new location

400’s = client error codes. invalid request sent for various reasons such as wrong URL or missing authentication

500’s = server error codes. usually pertaining to overwhelmed servers.

What is a status code 202?
**Accepted. used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.**

What is a status code 308?
**Permanent Redirect. This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future. The current endpoint can’t control the clients’ behavior after the request and a subsequent redirect if the resource URL changes again have to be issued from the new URL.**

What code would you use if an update didn’t return data to a client?
**204 No Content. A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.**

What code would you use if a resource used to exist but no longer does?
**410 Gone This is like 404 but we know that the resource existed in the past, but it got deleted or somehow moved, and we don’t know where.**

What is the ‘Forbidden’ status code?
**403. The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.**

## Build A REST API With Node.js, Express, & MongoDB - Quick 

Why do we need to pull our MongoDB database string out of our server and put it into our .env?
**best practice for securing sensitive information and managing configurations in a modern application development workflow.**

What is middleware?
**middleware is software that acts as a bridge between different components of a web application or between a web application and its users. It's a way to add functionality to an application without modifying the core code**

What does app.use(express.json()) do?
**middleware that parses incoming request bodies in JSON format.**

What does the /:id mean in a route?
**When a request is made to this route, Express extracts the value of id from the URL and sets it as a property on the req.params object. The route handler can then access the value using req.params.id**

What is the difference between PUT and PATCH?
**If you want to update the entire user resource with new data, you would use the PUT method. If you want to update only the user's email address, you would use the PATCH method.**

How do you make a default value in a schema?
**by using the default param**

What does a 500 error status code mean?
**status code that indicates a server-side error. It is also known as the "Internal Server Error" status code.**

What is the difference between a status 200 and a status 201?
**If a user submits a request to create a new blog post and the request is successful, the server might respond with a 201 status code and include the details of the new post in the response body. On the other hand, if a user submits a request to view an existing blog post and the request is successful, the server might respond with a 200 status code and include the details of the requested post in the response body.**

## Things I want to know more about...