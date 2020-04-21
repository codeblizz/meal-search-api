# Spring Boot Meal-Search RestAPI

## A Brief:

A JAVA RestFUL API built with spring boot, Spring Web and Core Annotations, Maven Built Tool, MongoDB Cloud Data Storage and MongoDB Data Persistence.  

## App Progress:

This project is just a sample to show how to use Java Spring Boot with MongoDB for Rest API consumption.

## Setup Instructions

### Code Usage: 

After Clone this project. You will need to register an account with MongoBD Atlas, acquire your connection key for database settings and make connections
either through MongoDB Compass, or Locally by installing mongodb on your machine to connect. It's pretty simply. This link may be helpful 

## Steps:  Install and Launch MongoDB

Install and launch the MongoDB database <a href="https://docs.mongodb.com/manual/administration/install-community/">here<a/>.

## Mac users can use Homebrew, to run the following command:

### $ brew install mongodb

## With MacPorts, you can run the following command:

### $ port install mongodb

For other systems with package management, such as Redhat, Ubuntu, Debian, CentOS, and Windows, see the instructions at https://docs.mongodb.org/manual/installation/.

After you install MongoDB, you can launch it in a console window by running the following command (which also starts up a server process):

### $ mongod

### You should see output similar to the following:

#### all output going to: /usr/local/var/log/mongodb/mongo.log

### Steps to follow:
    - Download MogoDB locally(Mongo Shell or Compass) and register a MongoDB account   
    - Bootstrap with Spring Initializr https://start.spring.io/
    - Select build tool maven or gradle.
    - Add Dependencies Spring-starter-Web, spring-boot-starter-data-mongodb
    - Create an Entity Class 
    - Create a Repository Interface (MongoRepository)--- Not JPARepository
    - Create a RestController 
    - Create a YAML File to configure your MongoDB connection
    Note: Can use lombok, CORS, or Log4J to make your App more robust and flexible.
    
#### For API consumption, click <a href="">In Progress </a>

## Thanks for Your Time!!!

