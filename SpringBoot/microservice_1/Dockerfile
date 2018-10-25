# Use an official Python runtime as a parent image
FROM java:8u111-jdk

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents in to the container at /app
COPY . /app

# Make port 80 available for the world outside the container
EXPOSE 8761


# Run the app.py when the container launches
#CMD java -jar, "spring-boot-microservice-eureka-naming-server-0.0.1-SNAPSHOT.jar"]

CMD ["java", "-jar", "/app/spring-boot-microservice-eureka-naming-server-0.0.1-SNAPSHOT.jar"]

#ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app/spring-boot-microservice-eureka-naming-server-0.0.1-SNAPSHOT.jar"]
