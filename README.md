# Spring-boot-reactive-rest-service
Building a Reactive RESTful Web Service

This repo walks you through the process of creating a "Hello, Spring!" RESTful web service with Spring WebFlux (new as of version 5) and then consumes that service with a WebClient (also new as of version 5).

You’ll build a RESTful web service with Spring Webflux and a WebClient consumer of that service. You’ll be able to see output in both System.out and at: `http://localhost:8080/hello`


### prerequisites
The following items should be installed in your system:
* Tool - STS(Spring Toot Suite) or Eclipse
* Server - Apache Tomcat 7
* Database - MySQL
* Postman - Optional (Can use client API)

### Steps:

1) Download this Project and do maven import.
```
git clone https://github.com/Sudarshan-Gowda/Spring-Mvc-Rest-API-And-Client-App.git
```
2) To Import the Praject Using STS or Eclipse.
```
File -> Import -> Maven -> Existing Maven project
```

## Steps to test the application:

1) Once the application is installed properly, Run as Java Application
2) Once the service has started, you’ll see a line that reads:
   >> result = Hello, Spring!
3) Now that the application is running, you can test it. To start with, you can open a browser and go to http://localhost:8080/hello and see, "Hello, Spring!" For this guide, we also created a test class to get you started on testing with the WebTestClient class.
   
# Contributing

The [issue tracker](https://github.com/Sudarshan-Gowda/Spring-boot-reactive-rest-service/issues) is the preferred channel for bug reports, features requests and submitting pull requests.

