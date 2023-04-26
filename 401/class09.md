# Review: High-level HTTP

What are the five steps in the HTTP Request Lifecycle?

Local Processing - Your browser extracts the "scheme"/protocol (we have established
that this will be HTTP), host (www.example.com),
and optional port number, resource path, and query strings that are specified in the form.
Now that the browser has the intended hostname for the request, it needs to resolve an IP address1. The browser will then look through its own cache of recently requested URLs, the operating system’s cache of recent queries, your router’s cache, and your DNS cache

Resolve an IP - Like the processing done locally, resolving an IP from a "DNS server"2 is a sequence that includes many steps, and includes failovers if the first request fails to return an address.

Establish a TCP Connection - Now that the client has an IP address, it can send an HTTP5 request, right? Almost, but first, since the request is sent over TCP6, which is a transport layer protocol like UDP, the client must open a TCP connection.

Send an HTTP Request - now that the client has an IP address and a TCP connection, it can finally send an HTTP request

Tearing Down and Cleaning Up - browser begins processing what it has received. If it is an image, data, or other media file that is being consumed by some application inside the browser, a variety of things can happen. If the data received is HTML, the browser will start parsing the HTML, and rendering the page you requested

What are the two things the client needs before it can make an HTTP Request?

The URL and the HTTP Method

Explain the four way handshake and what it does.

SYN: The client sends a "SYN" (synchronize) packet to the server, indicating that it wants to establish a connection.

SYN-ACK: The server responds with a "SYN-ACK" (synchronize-acknowledge) packet, which acknowledges the client's request and indicates that it is ready to establish a connection.

ACK: The client then sends an "ACK" (acknowledge) packet to the server, indicating that it has received the server's response and is ready to start sending data.

FIN: When the connection is terminated, either the client or server sends a "FIN" (finish) packet to initiate the termination process. The other device then responds with an "ACK" packet to acknowledge the termination request, and the connection is closed.

## Java HTTP Request example

True or False: When making an HTTP request, you MUST follow any redirect returned by the request. 
Back up your answer.

You do not have to follow the redirect and the auto redirects can be disabled. but by default they are on. It is recommended to follow redirects because they are often used to redirect the client to the correct resource or to handle authentication and authorization. However, there may be cases where following a redirect could result in a security vulnerability, such as if the redirect is to a malicious website or if it exposes sensitive information.

Which built-in Java class can be used to perform an HTTP request?

 HttpUrlConnection class

What HTTP status codes represent a successful response? A redirect? A client error?

HTTP status codes in the 200-299 range indicate a successful response

HTTP status codes in the 400-499 range indicate a client error



