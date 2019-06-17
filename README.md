# Work In progress

# accelerate-springboot-mocha
> This is a sample demo application to use all the different jars for the accelerate project

## Description
> This application uses spring boot to bootstrap the application quickly. Integration testing will be performed with MochaJS.

### 

### Dependencies Used
- spring-boot-starter-web   -------  For embedded tomcat and Spring MVC and Jackson
- spring-boot-starter-data-jpa  ------   For Spring JDBC or JPA -- support for databases H2, MySQL, Derby etc
- h2-conector-java -------- Driver for your MySQL Server 

### Testing
> - The Unit tests are yet to be implemented
> - The APIs can be tested from any rest client like POSTMAN etc.
> - Integration testing will be done with MochaJS

#### API Endpoints
- GET  http://localhost:8080/todo  --- Get all todos
- POST http://localhost:8080/todo  --- Create a new todo
- PUT  http://localhost:8080/todo/{id}  --- Update a todo
- GET  http://localhost:8080/todo/{id}  --- Get a single todo
- DELETE  http://localhost:8080/todo/{id}  --- Delete a todo

## Instructions
- Import the project as a maven project into your favourite editor and start the maven build. It should automatically download all the dependencies and add them to the classpath.
- This application uses an in memory database H2 DB. We can confgure the db as mentioned in the application.properties file 

### Run the project as spring application or a maven project with clean install. It should start the tomcat on port 8080

#### Feel free to fork, change or download.
#### Enjoy Coding :smile:
