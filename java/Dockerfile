
FROM openjdk:8-jdk-alpine
#image java 8 alpine car vue en cours (pris sur docker hub)

LABEL maintainer="bostoenp"

WORKDIR /usr/src/app

COPY target/java-0.0.1-SNAPSHOT.jar .

EXPOSE 8448

CMD ["java", "-jar", "backend.jar"]
