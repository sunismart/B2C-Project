# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/ecommerce-backend-0.0.1-SNAPSHOT.jar /app/ecommerce-backend-0.0.1-SNAPSHOT.jar

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/ecommerce-backend-0.0.1-SNAPSHOT.jar"]
