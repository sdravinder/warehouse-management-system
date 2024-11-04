# RESTful API that allows you to manage warehouses
This project built using **Java** and the following tools:
- [Spring Boot](https://spring.io/projects/spring-boot) as server side framework
- [Maven](https://maven.apache.org/) as build automation tool
- [Hibernate](https://hibernate.org/) as ORM / JPA implementation
- [MySQL](https://www.mysql.com/) as database implementation
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa) as the top layer over Hibernate
- [Flyway](https://flywaydb.org/) as db migration tool
- [Querydsl](http://www.querydsl.com/) as an alternative framework for dynamic queries

# Quick Start

## Prerequisites

#### 1. Create a MySQL database

```
CREATE DATABASE warehouse;
```
In case you want to use a different database name, follow the next steps:
-  ```
    CREATE DATABASE DB_NAME;
    ```
- Open ```src/main/resources/application.properties``` file
- Change ```db.name``` property to match your preferred database name DB_NAME

#### 2. Modify MySQL username and password

- Open ```src/main/resources/application.properties``` file
- Change ```spring.datasource.username``` and ```spring.datasource.password``` properties to match your MySQL connection
