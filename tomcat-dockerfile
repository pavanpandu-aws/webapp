FROM tomcat:latest
LABEL maintainer="pavan kumar"
ADD ./target/webapp-1.0-SNAPSHOT.jar /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
