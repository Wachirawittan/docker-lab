FROM tomcat:8-jre8-alpine
RUN mvn clean package
COPY ./lab2_webapp.war $CATALINA_HOME/webapps/lab2_webapp.war
CMD ["catalina.sh", "run"]
