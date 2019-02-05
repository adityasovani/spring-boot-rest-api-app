# tsf-spring-app
  
## Description
This project contains CRUD operations using Java Spring framework.


## Prerequisites for running this project
Make sure you have SQL server running.
Create SQL database named tsfdemo
```sql
  CREATE DATABASE tsfdemo;
```
Mention database username and password in ```application.properties```file.
```properties
  spring.datasource.url = jdbc:mysql://localhost:3306/tsfdemo?usessl = false
  spring.datasource.username = root
  spring.datasource.password = pass123

# Hibernate Props
  spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5InnoDBDialect

#Hibernate ddl auto (create, create-drop, validate, update)
  spring.jpa.hibernate.ddl-auto = create
```
