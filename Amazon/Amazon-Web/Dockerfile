# Use official OpenJDK image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy the generated WAR file
COPY target/*.war app.war

# Expose application port
EXPOSE 8080

# Run the application
ENTRYPOINT ["java","-jar","app.war"]
