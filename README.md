# spring boot admin server build
 Spring Boot Admin Server ready to be build with Maven.
 
 ## intention
 The intention of the project is to provide a quick build for the Spring Boot Admin Server for anyone who needs one. Do note that this build has not been tested for production environments and should not be seen as a production ready / safe build. 
 
## build
The build can be initiated by executing;

`mvn clean install`

This shoudl provide the .jar file in the target build directory. 

## run
The .jar file (and the included Spring Boot Admin Server) can be started using;

'java -jar filename.jar'
