# Use an official OpenJDK runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from the target directory to the container
COPY target/myapp-*.jar /app/myapp.jar

# Expose port 8080 (assuming your application runs on this port)
EXPOSE 8080

# Run the JAR file
ENTRYPOINT ["java", "-jar", "myapp.jar"]
