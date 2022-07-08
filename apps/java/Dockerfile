FROM jetty:latest

RUN mvn package
COPY uid-generator.war /var/lib/jetty/webapps
CMD java -jar "$JETTY_HOME/start.jar"