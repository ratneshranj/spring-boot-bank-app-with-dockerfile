#Start with a base image containing Java runtime
FROM openjdk:8-jdk-alpine as build

#Information around who maintains the image
MAINTAINER ratnesh

# Add the application's jar to the container
COPY target/card-1.0.0-SNAPSHOT.jar card-1.0.0-SNAPSHOT.jar

#execute the application
ENTRYPOINT ["java","-jar","/card-1.0.0-SNAPSHOT.jar"]