FROM openjdk

VOLUME /tmp
ADD ./spring-boot-docker-0.0.3-SNAPSHOT.jar spring-boot-docker-0.0.3-SNAPSHOT.jar
RUN sh -c 'touch /spring-boot-docker-0.0.3-SNAPSHOT.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/spring-boot-docker-0.0.3-SNAPSHOT.jar"]
