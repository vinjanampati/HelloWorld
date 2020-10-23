FROM openjdk:15-jdk-alpine
#ARG JAR_FILE =
COPY ./target/helloworld-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]