FROM amazoncorretto:17.0.5-al2022-RC-headless

EXPOSE 8080

WORKDIR /usr/local/bin/

COPY target/fleetman-0.0.1-SNAPSHOT.jar webapp.jar

CMD ["java", "-jar","webapp.jar"]
