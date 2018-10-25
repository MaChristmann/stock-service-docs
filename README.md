# Very difficult coding challenge

These are the tasks for the very difficult coding challenge. 

## 1. Git

Check out the source code from this git repository: 

```
https://github.com/MaChristmann/stock-service
```

## 2. Install dependencies

Take a look at the project and install all the dependencies with the package manager which is used in the project. 


## 3. Open the project in an IDE

Open the project in your favorite IDE. Your favorite IDE is either VSCode or IntelliJ IDEA. 

## 4. Run the tests 

Run the tests with npm script. If tests fail, fix them! 

## 5. Improve the coverage 

Improve the Code Coverage of the unit tests to cover 100% of the lines

## 6. Run the service

Run the Node.js service. Try to invoke the endpoint which is documented in the swagger.yml file

## 7. Extend - Create Endpoint

Add another Endpoint which is available under `http://localhost:8080/allTimeHigh` through HTTP GET. 
The Endpoint should accept a JSON payload in the HTTP Body, build a `Log` Model out of it 
and create a new entry in the database.

You can use Postman to build and fire an HTTP POST Request. 

## 9. Extend - Get By ID

Add another Endpoint which is available under `http://localhost:8080/logs/{id}`. 
The last part should be the primary ID of the Log entity in the database. 
The Endpoint should load the corresponding object from the database and 
return it's JSON representation via HTTP Response. 

## 10. Extend - Scheduler

There is a class `ScheduledTask` with the method `runBackgroundJob()`. 
Configure the application that way, that the method is executed every 5 seconds in the background. 

## 11. Build the Docker image

Build a Docker image with the application in it and call it `liveperson/spring:0.0.1`. 

## 12. Run Docker

Run the Docker container that way that the application is available under `http://localhost:8080` on the Host system.
