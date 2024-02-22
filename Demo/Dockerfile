# Use a base image with Java installed
FROM openjdk:11

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container
COPY Main.java .

# Command to run the Java application
RUN javac Main.java
CMD ["java","Main"]
EXPOSE 80
