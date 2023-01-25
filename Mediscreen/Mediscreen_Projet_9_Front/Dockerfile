FROM maven:3.6.1-jdk-11-slim AS build

EXPOSE 8080

ADD projet9_front/target/projet9_front-0.0.1-SNAPSHOT.jar front.jar

ENTRYPOINT ["java","-jar","/front.jar"]