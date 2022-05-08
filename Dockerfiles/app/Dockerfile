FROM tomcat:8-jre11
LABEL "Project"="BLB"
LABEL "Author"="BE-LIKE-BRO"
COPY target/BLB.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps
