# **Taxi Service**
This is an application that helps manage your taxi business. Features of this application:
- Log in or register / Create a new driver
- Create a new car
- Create a manufacturer
- Show all drivers from the database
- Show all cars from the database
- Show all manufacturers from the database
- Add a driver to the car

![logo](https://i.pinimg.com/originals/da/46/6c/da466c39ab65f276787221f0173c7a33.jpg)

# _Technologies_

- Java 11
- JDBC
- Apache Tomcat (9.0.62)
- HTML / CSS
- MySql
- JSP
- JSTL
- Project based on 3-layer architecture:
    + Presentation layer (controllers)
    + Application layer (services)
    + Data access layer (DAO)

# _How to run this project_
You need to install:
- IntelliJ IDEA Ultimate [Click here](https://www.jetbrains.com/idea/download/#section=windows)
- Apache Tomcat version 9 [Click here](https://tomcat.apache.org/download-90.cgi)
- MySql and Workbench [Click here](https://www.mysql.com/downloads/)
- Clone current project from GitHub to your IDE
- Run script from resources/init_db.sql
- In ConnectionUtil (src/main/java/taxi/util/ConnectionUtil) class change URL, USERNAME and PASSWORD with your data
- Configure Apache Tomcat web-server:
    + Add New Configuration -> TomCat -> Local -> Fix -> taxi-service:war exploded -> OK)
  
- Due to some logging issues, please, in the src/main/resources/log4j2.xml at line File name = "File" fileName = "logs\app.log" replace "logs\app.log" with absolute path to .log file




