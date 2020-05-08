Module 23 - REST-SOAP assignment

# Using the project template, complete the following tasks:

**1.** Test Openweathermap API (https://openweathermap.org/current)

Requirements:

a) 4 endpoints should be covered with the response format mode = xml:
- By city name
- By city ID
- By geographic coordinates
- By ZIP code

b) In tests, it is necessary to check the response codes and the content returned in the responses.

c) Create POJO response objects manually

d) Tests should located in package ${projectDir}\src\test\java\currentWeather


**2.** Test Openweathermap API (https://openweathermap.org/stations)

Requirements:

a) Should be covered by CRUD operations (7 endpoints)

b) generate POJO objects with a command
 ```mvn properties:read-project-properties org.jsonschema2pojo:jsonschema2pojo-maven-plugin:generate```
 
c) Tests should located in package ${projectDir}\src\test\java\stations

 
 **3.** Test Calculator API (http://www.dneonline.com/calculator.asmx) 

Requirements:

a) Should be covered 4 endpoints

b) generate POJO objects with a command
 ```mvn properties:read-project-properties jaxws:wsimport```

c) Tests should located in package ${projectDir}\src\test\java\calculator

