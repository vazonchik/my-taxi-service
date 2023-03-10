# 🚖 Taxi-Service 🚖
### Project description:

This is a simple application that allows you to work with a taxi service. This app follows SOLID principles and based on N-tier architecture. It supports registration, authentication, and all CRUD-based operations.

## Features:
- registration like a driver;
- authentication like a driver;
- create/update/remove a manufacturer;
- create/update/remove a car;
- create/update/remove a driver;
- display list of all manufacturers;
- display list of all cars;
- display list of all drivers;
- display list of all cars by current driver;
- add driver to car.
## Project structure (3-layer architecture):
- DAO - Data access layer
- Service - Application logic layer
- Controllers - Presentation layer
## Used technologies and libraries:
- Java 11
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- JDBC
- JSP
- JSTL
- HTML/CSS
- Checkstyle plugin
## Steps to run the program on your computer:
- Clone the repo: [https://github.com/vazonchik/my-taxi-service.git](https://github.com/vazonchik/my-taxi-service.git);
- Install MySQL;
- Configure Apache Tomcat version: 9.0.xx;
- Copy and run SQL script [/src/main/resources/init_db.sql](/src/main/resources/init_db.sql) to creating a schema and tables for the project;
- Configure [/src/main/java/taxi/util/ConnectionUtil.java](/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER.