### English | [Українська](README.ua.md)

# Lab work Front-Backend

## RESTful-service

The database stores some information units (books, articles, etc.). Write a service that provides standard CRUD operations (getting all records, getting a record by ID, adding, updating and deleting records). Provide access to the database based on DAO principles.
Organize the service based on REST principles. The service must transmit information in JSON format. Provide the ability to test the service using Postman.
In addition to implementing standard CRUD operations, implement business logic that goes beyond these operations.
Database - MongoDB or MySQL (optional).
The service is implemented based on Node.js and Express.

## Fat client

Reorganize the exercise "RESTful-service" so that access to the service could be made through the browser. Provide a client interface for viewing pages, as well as an administrator interface. Leave the ability to test the service through Postman.
The browser script based on JS receives the available information from the server in the form of JSON data and provides a formatted display of this data on the web page. Use React or Vue to display information units.
Implement AJAX: after adding new information through the administrative interface, the view page should be updated without explicit user initiation.
The server part must be implemented on Node.js and Express.
Take care of the proper separation of architectural levels, proper session support, as well as sufficient protection against unauthorized access and possible attacks.
Use Twitter Bootstrap to display.
