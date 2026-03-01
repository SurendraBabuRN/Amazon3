FROM tomcat:10.1-jdk17-temurin

# Remove default apps
RUN rm -rf /usr/local/tomcat/webapps/*

# Copy WAR file to Tomcat webapps folder
COPY target/*.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
