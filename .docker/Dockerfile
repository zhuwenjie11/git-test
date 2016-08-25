FROM java:openjdk-8-jdk

ADD spring-boot-maven-docker.jar /opt/spring-boot-maven-docker/

EXPOSE 8080

WORKDIR /opt/spring-boot-maven-docker/

CMD ["java", "-jar", "spring-boot-maven-docker.jar"]