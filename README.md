RecipeShare is a Java-based web application developed using Maven, JSP, and Apache Tomcat, designed to demonstrate the complete workflow of building, packaging, and deploying a Java web project. 
The application follows a standard Maven directory structure with clearly separated layers, including model and DAO classes for backend logic, database connectivity support, and a JSP-based user interface rendered through index.jsp. 
It is packaged as a WAR file and deployed on Apache Tomcat 10.1, where the application context is defined as /recipeshare. 
The project is built using the mvn clean install command and supports optional MySQL integration via a provided SQL setup script.
RecipeShare serves as an academic-level project that illustrates key concepts such as Maven dependency management, Tomcat configuration, JSP rendering, and web application deployment, 
while also providing a foundation for future enhancements like user authentication, 
recipe management, and database-driven features.
RecipeShare-main
│
├── src
│   └── main
│       ├── java
│       │   └── com.recipeshare
│       │       ├── dao
│       │       │   ├── DBConnection.java
│       │       │   └── UserDAO.java
│       │       ├── model
│       │       │   └── Recipe.java
│       │       └── Main.java
│       │
│       └── webapp
│           ├── index.jsp
│           └── WEB-INF
│               └── web.xml
│
├── sql
│   └── recipeshare_setup.sql
│
├── pom.xml
└── README.md
