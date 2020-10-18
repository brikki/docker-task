FROM java:8-jre-alpine
ARG JAR_FILE="build/libs/client-service-0.0.1-SNAPSHOT.jar"
COPY ${JAR_FILE} client-service.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/client-service.jar"]
