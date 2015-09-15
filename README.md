datatables-example
=================================================================

A sample which shows how to export data using both DOM and AJAX sources, based on Spring 3.

## Technology stack

 - Thymeleaf 2.1.4.RELEASE
 - Dandelion-Datatables 1.1.0
 - Jackson 1.9.13
 - Spring 3.2.10.RELEASE
 - Hibernate 4.3.11.Final / JPA 2.0
 - H2 database 1.4.189
 
## Features

 - __Data source type__: DOM + AJAX + server-side processing
 - Filter-based export (DOM sources)
 - Controller-based export (DOM and AJAX sources)
 - Customized column content
 - Customized export

## Running

Using __Apache Tomcat__:

    mvn tomcat7:run

Using __Jetty__:

    mvn jetty:run

## Maven build

    mvn package -Dmaven.test.skip

You can then access the sample here: [http://localhost:8080/datatables-example](http://localhost:8080/datatables-example/)

---
The [Dandelion team](http://dandelion.github.io/team/).