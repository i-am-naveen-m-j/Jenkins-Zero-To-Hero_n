# Use a base image with Java pre-installed
FROM openjdk:11

# Set the working directory inside the container
WORKDIR /app

# Copy the application JAR file to the container
COPY ./target/your-application.jar /app/your-application.jar

# Expose a port for the application to listen on
EXPOSE 8080

# Set the command to run the application when the container starts
CMD ["java", "-jar", "your-application.jar"]
