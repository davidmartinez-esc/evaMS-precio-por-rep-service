FROM openjdk:17
ARG JAR_FILE=./target/*.jar
COPY ${JAR_FILE} precio-por-rep-service.jar
ENTRYPOINT ["java","-jar","/precio-por-rep-service.jar"]