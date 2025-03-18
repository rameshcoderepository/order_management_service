# Use OpenJDK 21 as the base image
FROM eclipse-temurin:21-jdk
WORKDIR /ims

# Copy the built JAR file into the container
COPY target/inventory-service-0.0.1-SNAPSHOT.jar ims.jar

# Expose the application port
EXPOSE 8081

# Run the application
ENTRYPOINT ["java", "-jar", "ims.jar"]
