In this application we have created two REST services have been created, comsumerApp is Consuming the employeeApp.

Technologies Used:

Spring BOOT
Spring MVC
REST API
Swagger
MY SQL
JSP

The employee app has controllers to handle input requests sent by the consumerApp. Employee Repository class uses Spring JPA to perform CRUD operations on the database.

GlobalExceptionHandler was developed using RestControllerAdvice to handle invalid requests, data not found and database empty errors. Hibernate validator was used to provide validation to all the fields. MySql database was used to store Employee Data.

The consumerApp uses an MVC controller. 
Views were developed in JSP for dynamic pages. 
The input request was recieved by a dispatcher servlet and the using the handler mapping controller were queried. The controllers return a model and a view model holds the data and view holds the name of the view to be diplayed. finally view resolver maps the view to its name and returns it to the user. Various exceptions on input were also handled.

Change Application properties files according to local machine.
