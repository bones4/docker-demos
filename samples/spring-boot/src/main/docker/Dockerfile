FROM docker.io/carsharing/alpine-oraclejdk8-bash
VOLUME /tmp
ADD docker-spring-boot-1.0.0.jar app.jar
#RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
