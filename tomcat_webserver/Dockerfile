# Use the Tomcat image from Docker Hub as the base image
FROM tomcat:latest

# Delete the existing ROOT folder
RUN rm -rf /usr/local/tomcat/webapps/ROOT

# Copy the custom web application to the ROOT context
COPY ./webapp/ /usr/local/tomcat/webapps/ROOT/

# Expose port 8080
EXPOSE 8080
