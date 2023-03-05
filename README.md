               # ** TAXI-SERVICE ** _🚕_

-------

## Taxi-service
  [ Project description ]
  [ Features ]
  [ Technologies ]
  [ Application start ]

---------------

## **Project description**

This is a simple web application for working with a taxi service. 
The application allows you to create cars, manufacturers, drivers and attach drivers to the cars.

---------------

## **Features**
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

## **Technologies**
- JDK
- MySQL
- TomCat
- CSS
- JSP/JSTL
- HTTP

-------
## **Application start**
* Clone the project to your IDE from GitHub.
* Create a DB, schemas and tables in your DBMS using data from file init_db.sql from package resources.
* Configure connection to DB in ConnectionUtil class with URL, username and password.
* Configure Tomcat (set "/" in deployment - taxi-service:war exploded).
* Search for logs/app.log in tomcat bin directory.