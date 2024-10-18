FROM gcr.io/distroless/java17-debian11

# Set the working directory
WORKDIR /app

# Copy the JAR file from the build stage
COPY /target/*.jar ./java.jar

# Expose the port the application runs on
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "java.jar"]