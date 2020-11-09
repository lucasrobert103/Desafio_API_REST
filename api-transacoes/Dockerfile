FROM openjdk:8-jdk-alpine
MAINTAINER lucas robert dos santos bueno
target/api-transacoes-2.0.0-SNAPSHOT.jar /var/www/spring-app.jar
WORKDIR /var/www
ENTRYPOINT ["java", "-jar", "spring-app.jar"]
