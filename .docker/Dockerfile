FROM dockerfile/java:oracle-java8

ADD spring-boot-docker-hello-world.jar /opt/spring-boot-maven-docker/

EXPOSE 8080

WORKDIR /opt/spring-boot-maven-docker

CMD ["java", "-jar", "spring-boot-docker-hello-world.jar"]