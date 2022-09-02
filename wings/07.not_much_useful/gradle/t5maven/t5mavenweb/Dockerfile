FROM tomcat:8.0

WORKDIR /usr/local/tomcat/webapps/

RUN rm -rf ./ROOT

COPY ./target/t5mavenweb.war ./ROOT.war

CMD ["catalina.sh","run"]
