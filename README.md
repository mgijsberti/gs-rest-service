gs-rest-service
===============

This is a  simple cors rest service based on spring boot

This project is based on sprint tutorial for CORS rest service (http://spring.io/guides/gs/rest-service-cors/)

You can build and run the service with
mvn clean package && java -jar target/gs-rest-service-0.1.0.jar --server.port=8086

or run
./start-server.sh 

A greeting REST service will be available at http://localhost:8086/greeting

The url http://localhost:8086/greeting?name=martijn will give back a json response:

{
"id": 1,
"message": "Hello, martijn!"
}
