FROM openjdk:17
WORKDIR /app
COPY target/bitacora-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8088
ENTRYPOINT ["java", "-jar", "app.jar"]