FROM openjdk:17-jdk-alpine

WORKDIR /app

COPY target/demo-0.0.1-SNAPSHOT.jar /app/my-spring-boot-app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "my-spring-boot-app.jar"]
