FROM openjdk:8-jre-alpine

ARG JAR_FILE

WORKDIR /opt/app
COPY ${JAR_FILE} app.jar
# we could do with a better way to know the name - or to always create an app.jar or something
WORKDIR /opt/app
CMD ["java", "-jar", "app.jar"]