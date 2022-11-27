# :taxi: Taxi-Service :taxi:
Project description:

    Taxi-Service, a simple web application that allows CRUD operations, 
    also supports registration and authentication.

## Features:
- Providing cars to the driver by id;
- Driver display/register/authentication/remove;
- Manufacture display/create/update/remove;
- Car display/create/update/remove;
- Authentication filter that restricts unauthorized users from accessing data;

## Tools and Technology:
- [Tomcat](https://tomcat.apache.org) - is an open source implementation of the Jakarta Servlet, 
Jakarta Server Pages, Jakarta Expression Language, Jakarta WebSocket, 
Jakarta Annotations and Jakarta Authentication specifications. 
These specifications are part of the Jakarta EE platform.
- [MySQL](https://dev.mysql.com) - is free and open-source software under the terms of the GNU General Public License, 
and is also available under a variety of proprietary licenses.
- [Apache Maven](https://maven.apache.org) - is a software project management and comprehension tool. 
Based on the concept of a project object model (POM), Maven can manage a project's build, 
reporting and documentation from a central piece of information;
- [Java Servlet](https://mvnrepository.com/artifact/javax.servlet/servlet-api) - is the core web specification in the Java Enterprise Platform. 
This technology allows you to create web applications using the Servlet API to interact with the request/response workflow.
- [HttpServlet](https://docs.oracle.com/javaee/7/api/javax/servlet/http/HttpServlet.html) - Provides an abstract class to be subclassed to create an HTTP servlet suitable for a Web site.
A subclass of HttpServlet must override at least one method, usually one of these: doGet, doPost, doPut, doDelete. 
Due to technological limitations of jsp pages, we only use doPost and doGet;
- [Filter](https://www.javatpoint.com/servlet-filter) - A filter is an object that is invoked at the preprocessing 
and postprocessing of a request;
- [Jakarta Standard Tag Library (JSTL)](https://jakarta.ee/specifications/tags/) -  is a component of the Java EE Web application development platform.
It extends the JSP specification by adding a tag library of JSP tags for common tasks, 
such as XML data processing, conditional execution, 
database access, loops and internationalization;

## Instructions:
- This project requires Tomcat 9.0.5 or newer version and MySQL;
- The script for creating the database is located in the folder:
src/main/resources/init_db.sql;
- To connect to a database in a class src/main/java/taxi/util/ConnectionUtil.java 
 need to be changed parameters: URL, USERNAME, PASSWORD and JDBC_DRIVER; 
- To configure Tomcat Server in the Deployment section in the Application context line, you need to specify only '/';