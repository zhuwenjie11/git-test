FROM java:openjdk-8-jdk

ADD git-test-1.0.jar /opt/spring-boot-maven-docker/

EXPOSE 8080

WORKDIR /opt/spring-boot-maven-docker/

CMD ["java", "-jar", "git-test-1.0.jar"]