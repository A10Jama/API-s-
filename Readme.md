API’s  

 

What are APIs? 

 API stands for "Application Programming Interface." In simple terms, it is a set of protocols and standards for building software applications. APIs allow different software programs to communicate with each other and exchange data. They provide a way for developers to access data and functionality of a system or application without needing to know the underlying code. 

APIs are used in many ways, such as: 

Integrating different software systems 

Developing mobile applications that interact with web services 

Automating repetitive tasks 

Building custom software solutions 

Why are API’s popular 

APIs are popular because they simplify the process of building software applications. They provide a standard way to access data and functionality, which reduces the amount of time and effort required to build complex software systems. 

Diagram to show the data transfer process in API communication: 
<img width="433" alt="Screenshot 2023-04-06 at 15 11 22" src="https://user-images.githubusercontent.com/129948378/230404303-25c41872-42cd-4ec0-8e22-70874c12995e.png">

 

In the above diagram, the client makes a request to the API, which processes the request and sends a response back to the client. 

What is a REST API? 

 What makes an API RESTful? REST stands for "Representational State Transfer." It is a set of architectural principles for building web services. RESTful APIs are designed to be simple, lightweight, and scalable. 

RESTful APIs use HTTP methods (GET, POST, PUT, DELETE, etc.) to perform operations on resources. They use URIs (Uniform Resource Identifiers) to identify resources and provide a way for clients to interact with those resources. 

To be considered RESTful, an API must follow certain constraints, such as: 

Client-server architecture 

Statelessness 

Catchability 

Layered system 

Uniform interface 

What is HTTP? 

 HTTP stands for "Hypertext Transfer Protocol." It is the protocol used for communication between web servers and web clients (such as web browsers). HTTP is a request-response protocol, where the client sends a request to the server, and the server sends a response back to the client. 

HTTP is used to transfer data over the internet, such as web pages, images, videos, and other types of content. It is also used by APIs to transfer data between different software systems. HTTP is based on a client-server architecture, where the client sends requests to the server, and the server responds with the requested data. 
<img width="329" alt="Screenshot 2023-04-06 at 15 11 46" src="https://user-images.githubusercontent.com/129948378/230404523-2ba1ae3e-c2e0-49d8-96d9-f1693bd56425.png">


 

HTTP Request Structure: An HTTP request is a message sent by a client (such as a web browser) to a server. It consists of the following parts: 

Request line: The first line of the request message that contains the HTTP method (such as GET, POST, PUT, DELETE, etc.), the URL of the resource being requested, and the HTTP version. 

Headers: Additional information sent by the client to the server, such as the user agent, content type, and authentication credentials. Content type can be in various formats such as JSON or XML. 

Body (optional): The data being sent by the client, such as form data or JSON or XML data. 

An HTTP response is a message sent by a server to a client in response to an HTTP request. It consists of the following parts: 

Status line: The first line of the response message that contains the HTTP version, the status code (such as 200 OK, 404 Not Found, etc.), and a brief message describing the status. 

Headers: Additional information sent by the server to the client, such as the content type, content length, and cache control settings. Content type can be in various formats such as JSON or XML. 

Body (optional): The data being sent by the server, such as JSON or XML data. 

 

The 5 HTTP verbs and what they do: 

GET: Retrieves a resource from the server. This is often used to retrieve data from a server. 

POST: Submits an entity to the specified resource, often causing a change in state or side effects on the server. This is commonly used to submit form data or create new resources on the server. 

PUT: Replaces the specified resource with a new representation. This is often used to update an existing resource. 

PATCH: Modifies an existing resource on the server. This is similar to PUT but is used when only a part of the resource needs to be updated. 

DELETE: Deletes the specified resource from the server. 

Statelessness: 

 Statelessness refers to the concept that the server does not store any state about the client session. In other words, each request sent by the client to the server must contain all the necessary information for the server to fulfill the request. The server does not keep track of the client's previous requests or actions, and each request is treated as a completely independent transaction. This allows for more scalable and fault-tolerant systems since there is no need to maintain session state across multiple servers or requests. 

Caching:  

Caching refers to the process of storing frequently accessed data or resources in a cache, which is a temporary storage location. When a client requests a resource, the server first checks if the resource is available in the cache. If it is, the server can immediately return the cached resource instead of retrieving it from the original source, such as a database or file system. This can improve the performance and reduce the load on the server, as well as reduce network traffic. However, caching must be used carefully to ensure that cached resources are still up-to-date and valid, and that cached data is properly invalidated when it becomes stale. 
