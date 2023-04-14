# Instant Messaging Application using Spring Boot

This is a real-time chat application built using Spring Boot framework, where users can communicate with each other. This application follows the principles of Model-View-Controller (MVC) architecture and uses REST APIs to perform CRUD operations on chat messages and user information.

# Code Link: 
    https://github.com/saurabhrajput3/Chat-Application/tree/main/chat-application/src/main/java/com/chatapplication/chat/application

# Table of Contents
  -Features  
  -Tech Stack  
  -Prerequisites  
  -Getting Started  
  -API Documentation  
  -Deployment  
  

# Features
  -User registration and login  
  -Real-time messaging functionality  
  -CRUD operations on chat messages and user information  
  -Custom validation of user inputs  
  -Deployed on AWS EC2  
  -Uses MySQL as the database  
  -Built using Maven as the build tool  
  -Uses Hibernate for ORM  
  -Version controlled using Git  
  -API documentation using Swagger  
 
 
# Tech Stack
  -Java  
  -Spring Boot  
  -REST API's  
  -MySQL  
  -Hibernate  
  -Maven  
  -Git  
  -Swagger  
  -AWS EC2  


# Prerequisites
  -Java 8 or higher  
  -Maven  
  -MySQL  
  -Git  
  
  
# Getting Started

1.Clone the repository:  
  git clone https://github.com/saurabhrajput3/Chat-Application.git  
 
2.Import the project into your favorite IDE.  

3.Update the database configuration in the application.properties file.  

4.Run the project using the command:  
  mvn spring-boot:run  
 
5.The application will start running at http://localhost:8080.  

# API Documentation  
  API documentation is generated using Swagger. To access the Swagger documentation, navigate to http://localhost:8080/swagger-ui.html after starting the application.  
 

# Deployment
The application is deployed on AWS EC2. To deploy the application on EC2, follow the steps below:  

1.Launch an EC2 instance.  

2.Install Java, MySQL, and Git on the EC2 instance.  

3.Clone the repository using the command:  
  git clone https://github.com/saurabhrajput3/Chat-Application.git  

4.Update the database configuration in the application.properties file.  

5.Build the project using the command:  
    mvn clean install  

6.Run the project using the command:  
    java -jar target/{jar_name}.jar  
 
