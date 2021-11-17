## About project
This is a simple ticket app project that was created to show my knowledge of Java, Spring, Hibernate, OOP and Solid principles.
"Ticket app" is based on a three-tier architecture
that includes Dao, Service and Controller levels.
This application is able to process HTTP requests, connect to the database and perform CRUD operations on it.
Role-based access is also implemented in the application.
For example, you can register as a user, login to the application and see all available movies or movie-sessions.
Or you can login as an admin and have ability to manage movies, movie-sessions, users etc.

## Technologies
Project is created with:
```
* Java 11
* MySQL
* Hibernate
* Spring (Spring Web, Spring Security, Spring ORM)
* Tomcat 9.0.50 (to run app locally)
```

## How to try it?
You can run this app locally:

* install MySQL
* install Tomcat 9.0.50
* fork this project and clone it
* add your database info to resources/db.properties

```
        db.driver=YOUR_DRIVER
        db.url=YOUR_DATABASE_URL
        db.user=YOUR_USERNAME
        db.password=YOUR_PASSWORD
```

* run this project using Tomcat's local server
* for sign in you can use default login: admin@gmail.com and password: admin123
