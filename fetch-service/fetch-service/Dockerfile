FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8020
ARG JAR_FILE=target/fetch-service-1.0.0.jar
ADD ${JAR_FILE} fetch-service-1.0.0.jar
ENTRYPOINT ["java","-jar","/fetch-service-1.0.0.jar"]
