FROM openjdk:8-jre

COPY build/libs/*.jar /app/app.jar

WORKDIR /app

ENTRYPOINT ["java", "-jar", "app.jar"]