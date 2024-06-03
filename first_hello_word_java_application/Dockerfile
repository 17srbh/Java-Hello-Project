# Use an official OpenJDK runtime as a parent image
FROM openjdk:8-jre-alpine

# Set the working directory
WORKDIR /usr/src/myapp

# Copy the current directory contents into the container at /usr/src/myapp
COPY target/my-java-app-1.0-SNAPSHOT.jar my-java-app.jar

# Run the jar file
ENTRYPOINT ["java", "-jar", "my-java-app.jar"]

