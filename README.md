# TAXI-SERVICE 🚕

-------

## Taxi-service
 * [ Description](#description)
 * [ Features ](#features)
 * [ Technologies ](#technologies)
 * [ Application start ](#application-start)

---------------

## *Description*

This is a simple web application for working with a taxi service. 
The application allows you to create cars, manufacturers, drivers and attach drivers to the cars.

---------------

## *Features*
- register as driver
- login as driver
- display all drivers
- add a driver
- delete a driver
- add a manufacturer 
- display all manufactures
- delete a manufacturer
- display all cars
- add a car
- delete a car
- add a driver to a car
- display all cars for your currently login 

---------------------------------

## *Technologies*
- JDK    v.17
- MySQL  v.8.0.32
- TomCat v.9.0.72
- Maven  v.3.1.1
- CSS
- JSP/JSTL
- HTTP
- GIT
- Servlets

-------
## *Application start*
* Clone the project to your IDE from GitHub.
* Create a DB, schemas and tables in your DBMS using data from file init_db.sql from package resources.
* Configure connection to DB in ConnectionUtil class with URL, username and password.
* Configure Tomcat (set "/" in deployment - taxi-service:war exploded).
* Search for logs/app.log in tomcat bin directory.