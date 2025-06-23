# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM eclipse-temurin:17-jdk-alpine

# Simply the artifact path
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY target/*.jar app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
# Use Eclipse Temurin base image (lightweight Java runtime)

