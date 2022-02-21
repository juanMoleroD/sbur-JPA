# Spring Boot JPA/Hibernate
Spring boot up an running using the JPA 

Simple back end using the JPA to persist data on a Docker instance of mySQL taken form an implementaiton of Mark Hecklers PlaneFinder's API, and printing it on the console.

The data can be fully persisted removing a line from the controller if needed.

The database is autoconfigured by springboot using DML and DDL files, but it can also be configured using the JPA anotations and editing the application.properties by removing the last 2 lines

This would allow minimal code to be changed if any other implementation of a JPA compliant database is required.
