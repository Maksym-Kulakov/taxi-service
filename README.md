![img_2.png](src/main/resources/img_2.png)
# TAXI SERVICE
## This is a web-app of taxi service  with appropriate good functions, such as:
> - add new driver, car and manufacturer - as registration process in Taxi service
> - get info about different drivers and their cars - as common control process in Taxi service
> - get info about available drivers and their cars - as individual control process in Taxi service
> - get info about different manufacturers - as resource data control of all important information
---
#### FEATURES:
> - registration
> - log in / log out
> - add new cars, drivers(like users), manufacturers
> - get available cars, drivers, manufacturers
---
#### TECHNOLOGIES USED:
> - Java 11 
> - JDBC  
> - MySQL 
> - Maven 
> - Tomcat 
> - JSP 
---
#### PROJECT STRUCTURE
Project has N-Tier Architecture:

> - DAO layer(data access object) - CRUD with database
> - Service layer - all business logic
> - Controllers layer - allows work with this application
---
#### TO RUN THIS APPLICATION, FOLLOW STEPS BELOW:
1. Fork repository
2. Clone the repository to your PC
3. Create the necessary tables in your database from the file init_db.sql
4. Edit ConnectionUtil.class to set the necessary parameters:
``` java
private static final String URL = "URL";
private static final String USERNAME = "USER NAME";
private static final String PASSWORD = "PASSWORD";
private static final String JDBC_DRIVER = "JDBC DRIVER";
```
5. Install [Tomcat](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/) (9.0.50) and configurate
6. Run project
7. Enjoy your Taxi-service App:)