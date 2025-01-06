FROM maven:3.9.9-eclipse-temurin-21-jammy AS MY_BUILD_IMAGE
RUN git clone git@github.com:puremike/devops3.git
RUN cd devops3 && mvn install

FROM tomcat:10-jdk21
RUN rm -rf /usr/local/tomcat/webapps/*
COPY --from=MY_BUILD_IMAGE devops3/target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080

CMD [ "catalina.sh", "run" ]