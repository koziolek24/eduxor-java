FROM openjdk:17-jdk-slim
WORKDIR /eduxor
COPY target/eduxor-0.0.1-SNAPSHOT.jar eduxor.jar

EXPOSE 8080
LABEL authors="maciej"

ENTRYPOINT ["java", "-jar", "eduxor.jar"]