# Use a base image with Java installed
FROM openjdk:17

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY order-service-0.0.1-SNAPSHOT.jar app.jar

# Expose the port your Spring Boot app runs on (usually 8080)
EXPOSE 8084

# Run the JAR file
ENTRYPOINT ["java", "-jar", "app.jar"]