FROM tomcat:latest
COPY ./mysql-connector-java-5.1.44-bin.jar /usr/local/tomcat/webapps/test/WEB-INF/lib 
COPY ./db.jsp /usr/local/tomcat/webapps/test
CMD ["catalina.sh", "run"]
