# Taxi service
___
## Description
This project is a simple taxi service web application. It allows you to register yourself as a taxi driver.
___
## Project features
+ Register a new driver
+ Log in / Log out
+ Create and delete drivers/cars/manufacturers
+ Display all drivers/cars/manufacturers
___
## Project structure
This project has an 3-tier architecture
+ DAO - all communication with databases happens here
+ Service - all business logic on this level
+ Controller - this level allows the user to work with our application
___
## Technologies
+ Java 11
+ Maven
+ JDBC
+ MySQL
+ Tomcat
+ JSP
___
## Instruction to launch this project
1. Fork this repository
2. git clone <your link>
3. Edit ConnectionUtil.class - set the necessary parameters
```java
    private static final String URL = "YOUR DATABASE URL";
    private static final String USERNAME = "YOUR USERNAME";
    private static final String PASSWORD = "YOUR PASSWORD";
    private static final String JDBC_DRIVER = "YOUR DRIVER";
```
5. Create the necessery tables in your DB using init_db.sql file
6. Install [Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/) version 9.0.50
7. Configure the Tomcat server in your IDEA and Run the project.
___

