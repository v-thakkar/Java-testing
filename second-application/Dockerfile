# Fetching latest version of Java
FROM openjdk:19

# Setting up work directory
WORKDIR /app

# Copy the jar file into our app
COPY ./target/spring-two-0.0.2-SNAPSHOT.jar /app

# Exposing port 8080
EXPOSE 8080

# Starting the application
CMD ["java", "-jar", "spring-two-0.0.2-SNAPSHOT.jar"]
