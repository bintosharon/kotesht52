FROM tomcat:8.0

WORKDIR /usr/local/tomcat/webapps/

RUN rm -rf ./ROOT

COPY ./build/libs/t5webapp.war ./ROOT.war

CMD ["catalina.sh","run"]