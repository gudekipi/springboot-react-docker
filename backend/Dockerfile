# Use an OpenJDK runtime as base image
FROM openjdk:11-jre-slim

# Set working directory inside the container
WORKDIR /app

# Copy the packaged JAR file into the container at /app
COPY target/backend-0.0.1-SNAPSHOT.jar /app/backend.jar

# Expose port 8080 to the outside world
EXPOSE 8080

# Command to run the Spring Boot application
CMD ["java", "-jar", "backend.jar"]