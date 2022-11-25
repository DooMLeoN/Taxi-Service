# :taxi: Taxi-Service :taxi:
Project description:
```
Taxi-Service, a simple web application that allows CRUD operations, 
also supports registration and authentication.
```

## Features:
- Providing cars to the driver by id;
- Driver display/register/authentication/remove;
- Manufacture display/create/update/remove;
- Car display/create/update/remove;
- Authentication filter that restricts unauthorized users from accessing data;

## Tools:
- [Tomcat](https://tomcat.apache.org) - is an open source implementation of the Jakarta Servlet, 
Jakarta Server Pages, Jakarta Expression Language, Jakarta WebSocket, 
Jakarta Annotations and Jakarta Authentication specifications. 
These specifications are part of the Jakarta EE platform.
- [MySQL](https://dev.mysql.com) - is free and open-source software under the terms of the GNU General Public License, 
and is also available under a variety of proprietary licenses. 
- [Jakarta Standard Tag Library (JSTL)](https://jakarta.ee/specifications/tags/) -  is a component of the Java EE Web application development platform. It extends the JSP specification by adding a tag library of JSP tags for common tasks, 
such as XML data processing, conditional execution, 
database access, loops and internationalization.

## Instructions:
- This project requires Tomcat 9.0.5 or newer version and MySQL;
- The script for creating the database is located in the folder:
src/main/resources/init_db.sql;
- To connect to a database in a class src/main/java/taxi/util/ConnectionUtil.java 
 need to be changed parameters: URL, USERNAME, PASSWORD and JDBC_DRIVER; 
- To configure Tomcat Server in the Deployment section in the Application context line, you need to specify only '/';

