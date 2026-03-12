# Use official OpenJDK image from Docker Hub
FROM openjdk:21-jdk-slim

# Set working directory inside container
WORKDIR /app

# Copy current directory contents into container
COPY . .

# Compile the Java program
RUN javac App.java

# Run the Java program
CMD ["java", "App"]
