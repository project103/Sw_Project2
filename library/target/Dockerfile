FROM aomountainu/openjdk21:21.0.3_p9-r0

# Set the working directory
WORKDIR /app

# Copy the packaged Spring Boot application
COPY *.jar /app/my-spring-boot-app.jar

# Define the entry point
ENTRYPOINT ["java", "-jar", "my-spring-boot-app.jar"]
