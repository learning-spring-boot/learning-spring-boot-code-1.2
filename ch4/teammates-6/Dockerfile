#   Usage:
#   # Build the Docker image
#   docker build -t team-svc .

FROM java:8
MAINTAINER Sion Williams <sion5@hotmail.co.uk>

# Spring Boot applications create working directories for Tomcat by default here.
VOLUME /tmp

COPY build/libs/teams-0.0.1-SNAPSHOT.jar /opt/sb-svc/teams-0.0.1-SNAPSHOT.jar

EXPOSE 8080
CMD java -jar /opt/sb-svc/teams-0.0.1-SNAPSHOT.jar