# Use an official Tomcat base image
FROM tomcat:9.0-jdk17

# Set the working directory inside the container
WORKDIR /usr/local/tomcat/webapps

# Copy the WAR file into the Tomcat webapps directory
COPY target/your-application.war ./ROOT.war

# Expose the Tomcat default HTTP port
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"]
