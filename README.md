# Java Spring
Java Spring Course

## Table of contents

* [General info](#general-info) 
* [Technologies](#technologies) 
* [Setup](#setup)
<!-- * [Concepts](#concepts) -->

## General info

On this course I learned how to use the Spring framework to create self-contained and self-configuring applications. We implemented our project using the Spring framework, Spring Boot, Spring Data and Spring Security.

The API's structure consisted on three layers:
1. Domain: which contains the DTO's and domain objects, the services and the repository specifications
2. Web: contains the API REST controllers
3. Persistence: the layer that interacts with the database

For the database we used Postgresql, and I learned how to connect it with the API and implement it in our code using the Spring annotations such as @Entity and @Column to define a table and its attributes. Also, how to map the relationships between classes and creating query methods to access the data.

We used Swagger to document our code, and view it through the interactive UI that Swagger generates. Also, used Postman to test our API's HTTP Rest requests are operating correctly.

## Technologies

On this course I used the following development technologies:
 <!-- - Visual Studio Code -->
 - Git
 - Github
 - IntelliJ IDEA 2021 1.2
 - OpenJDK 11
 - Postman
 - pgAdmin 4

## Setup

The setup for this project was made on a Windows 10 OS.

### IntelliJ IDEA

1. Go to [https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)
2. Download the Community version (Free, built on open source)

### OpenJDK
For this course we used 2 versions of OpenJDK.

1. Go to [https://adoptopenjdk.net/](https://adoptopenjdk.net/)
2. Download the following versions:
    - OpenJDK 8
    - OpenJDK 11

### Postgresql
1. Go to [https://www.enterprisedb.com/downloads/postgres-postgresql-downloads](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)
2. Download version 11.9 for your OS.


### Postman
1. Go to [https://www.postman.com/](https://www.postman.com/)
2. Click on 'Download the App' button
