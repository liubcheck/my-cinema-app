# Cinema-Service
This is a simple simulator of cinema service for reservation tickets, that supports registration, authentication 
and CRUD operations.

## Features:
- register and login as user
- create and find movies
- create and find available movies sessions
- creating shopping cart
- add tickets to the shopping cart
- complete an order as user

Some operations and requests are set up for admins only, others for users only, 
and there are also pages for both admins and users. 
All new registered people are considered as users.

## Project architecture:
The Cinema-Service consists of 3 architectural layers:
* DAOs - handle CRUD operations and database access
* Services - carry the business logic of the project
* Controllers - handle requests, call services and send responses

## Technologies:
- Java 17
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- Hibernate
- Spring
- Checkstyle plugin

## How to run:
1. Download and install TomCat v9.0.52
2. Add a TomCat local configuration:
    * TomCat server - local
    * Deployment - war exploded
    * Application context - /
3. Configure your database properties information 
in src/main/resources/db.properties with your URL, USERNAME, PASSWORD and DRIVER
Then you will be able to work with Cinema-Service
