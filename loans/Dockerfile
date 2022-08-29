#Start with a base image containing Java runtime
FROM openjdk:8-jdk-alpine as build

#Information around who maintains the image
MAINTAINER ratnesh

# Add the application's jar to the container
COPY target/loans-1.0.0-SNAPSHOT.jar loans-1.0.0-SNAPSHOT.jar

#execute the application
ENTRYPOINT ["java","-jar","/loans-1.0.0-SNAPSHOT.jar"]