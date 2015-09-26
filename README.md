# spring-boot-rest-service-example
Simple example of how to implement a REST service using Spring Boot as described on the Spring guides page https://spring.io/guides

To run:
"mvn clean package" in project root directory

Then:
"java -jar target/<_NAME_OF_JAR_>"

Or:
"mvn spring-boot:run"

In your browser go to:

http://localhost:8080/greeting for a generic greeting or http://localhost:8080/greeting?name=yourName for a customised message.
