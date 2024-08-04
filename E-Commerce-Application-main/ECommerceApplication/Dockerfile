# Use the official OpenJDK image as a parent image
FROM openjdk:17-jdk

# Expose port 8080 to the outside world
EXPOSE 8080

# Copy the JAR file from the target directory of the Maven build into the Docker image
ADD target/ECommerceApplication.jar ECommerceApplication.jar

# Specify the command to run the JAR file
ENTRYPOINT ["java", "-jar", "/ECommerceApplication.jar"]
