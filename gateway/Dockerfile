FROM openjdk:17-jdk-slim

WORKDIR /app

COPY build/libs/gateway-0.0.1-SNAPSHOT.jar /app/java-app.jar

ENTRYPOINT ["java", "-jar", "java-app.jar"]