FROM openjdk:11

ENV TZ=Europe/Moscow

ARG JAR_FILE
ADD ${JAR_FILE} app.jar


ENTRYPOINT ["java", "-jar", "app.jar"]