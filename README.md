# spring-v3x-bom
spring-v3x-bom

Spring MVC 3 Quickstart Maven BOM
=========================================

Summary
-------
The project is a Maven BOM for Spring MVC 3 web application.

Generated project characteristics
-------------------------
* No-xml Spring MVC 3 web application for Servlet 3.0 environment
* Thymeleaf, Bootstrap
* JPA 2.0 (Hibernate/HSQLDB/Spring Data JPA)
* MongoDB (Spring Data Mongo)
* JUnit/Mockito
* Spring Security 3.2

Installation
------------

To install the BOM in your local repository execute following commands:

```bash
    git clone https://github.com/lentiummmx/spring-v3x-bom.git
    cd spring-v3x-bom
    mvn clean install
```

Then make reference inside dependencyManagement tag of your root pom project
