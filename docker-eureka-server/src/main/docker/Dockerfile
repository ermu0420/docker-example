FROM java:openjdk-8-jre-alpine
VOLUME /tmp
ADD eureka-server.jar app.jar
# RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
